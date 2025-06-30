# online-voting-face-blockchain
An AI and blockchain integrated image
# Online Voting System Using Face Recognition and Ethereum Blockchain

This project proposes a secure and intelligent Smart Voting System that integrates facial recognition and blockchain technologies to revolutionize the electoral process. The primary objective is to eliminate voter fraud, ensure transparent voting, and streamline the overall voting procedure through automation and biometric authentication.

## Features

- Face Recognition (OpenCV, LBPH) for voter authentication
- Ethereum Blockchain (Web3.py, Ganache) for immutable vote storage
- Admin and User (Voter) modules with secure registration, login, and voting
- Real-time result visualization
- Notifications via SMS/Email
- Scalable and adaptable for various election scenarios

## Team

- Putta Dilliprasad (21BCE9887)
- Sai Nithin Chinnakotla (21BCE9415)
- Suggam Raj Kumar (21BCE9911)

Under the guidance of Prof. Naga Jagadesh Bommagani  
School of Computer Science Engineering, VIT-AP University

## How to Run

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Set up MySQL and import the schema from `db.sql`
3. Start Ganache for the local Ethereum blockchain
4. Configure email and blockchain keys in `main.py`
5. Run the Flask app:
   ```
   python main.py
   ```
6. Access the web interface at `http://localhost:5000`

## Requirements

- Python 3.7+
- Flask, OpenCV, Pandas, Web3.py, PyMySQL, etc. (see requirements.txt)
- Ganache/Ethereum for local blockchain
- MySQL for backend database

For detailed documentation and report, see [REPORT.md](REPORT.md).

## License

This project is for academic purposes at VIT-AP University.

📚 Library Lending Blockchain
This project is a simple, unique implementation of a blockchain for a library lending system. It creates a secure and transparent ledger to track the borrowing and returning of books, preventing issues like lost records or disputes over due dates. The system is designed to be easily verifiable by both librarians and patrons.

🌟 Features
Immutable Records: All lending and return transactions are stored on a blockchain, making them permanent and tamper-proof.

Proof-of-Work (PoW): A simple mining process validates new blocks of transactions, ensuring data integrity.

Librarian Authorization: Only pre-registered librarians can add new book records and mine blocks, maintaining system security.

Transparent History: Anyone can verify a book's complete lending history, including who borrowed it and when it was returned.

Simple CLI: A user-friendly command-line interface allows for easy interaction with the blockchain.

🛠️ How It Works
The system operates on a few core principles:

Transactions: When a book is borrowed or returned, a transaction is created containing details like the book's title, the patron's name, and the action taken.

Pending Block: These transactions are held in a pool of pending transactions.

Mining: A librarian "mines" a new block by solving a computational puzzle (Proof-of-Work). This process bundles all pending transactions into a new, permanent block.

Chain Validation: Each new block contains a cryptographic hash of the previous block, linking them together in a chain. This ensures that any attempt to alter a record would break the chain, making the change immediately obvious.

🚀 Getting Started
Prerequisites
Python 3.x

Installation
Save the provided code into a file named library_blockchain.py.

Open your terminal or command prompt.

Navigate to the directory where you saved the file.

Usage
Run the program from your terminal:

Bash

python library_blockchain.py
Follow the on-screen menu to interact with the blockchain:

Option 1: Add a new book record (requires a valid Librarian ID).

Option 2: Mine the pending transactions into a new block.

Option 3: Display the entire blockchain, showing all validated records.

Option 4: Run a check to verify that the blockchain has not been tampered with.

Option 5: Look up a book's history by its title.

Option 6: Exit the program.

👥 Contributors
This project was developed as a simple demonstration of blockchain technology.

📄 License
This project is open-source and available under the MIT License.

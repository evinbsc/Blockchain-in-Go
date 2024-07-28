# Blockchain in Go

This project implements a basic blockchain in Go, providing a foundational understanding of blockchain technology. The blockchain records and validates heart rate data (beats per minute or BPM), and can be interacted with through a web server, allowing users to view and add new blocks to the chain.

## Purpose

The purpose of this project is to demonstrate how a simple blockchain works by:
- Creating a chain of blocks that securely records data.
- Utilizing hashing to maintain the integrity and order of the blockchain.
- Providing a web interface to view and add blocks to the blockchain.

## Features

- **Create your own blockchain**: Initialize a blockchain with a genesis block and add new blocks.
- **Hashing for integrity**: Use SHA256 hashing to ensure the integrity and proper order of blocks.
- **View blockchain in a web browser**: A simple web server allows you to view the blockchain in JSON format.
- **Add new blocks**: Send POST requests to add new blocks with heart rate data.
- **Resolve chain conflicts**: Implement a basic mechanism to choose the longest chain in case of conflicts.

## Setup

### Prerequisites

Ensure you have Go installed on your system. You can download it from [golang.org](https://golang.org/dl/).

### Installing Dependencies

You will need to install the following Go packages:

go get github.com/davecgh/go-spew/spew
go get github.com/gorilla/mux
go get github.com/joho/godotenv

- Spew: Allows you to view structs and slices in a clean format in the console.
- Gorilla/mux: A powerful URL router and dispatcher for Go.
- Godotenv: Loads environment variables from a .env file.

## Running the Project

Clone the repository:

git clone https://github.com/evinbsc/Blockchain_in_Go.git
cd Blockchain_in_Go

## Run the application:

go run main.go

Open your browser and navigate to http://localhost:8080 to view the blockchain.

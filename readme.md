# PBFT (Practical Byzantine Fault Tolerance) Implementation in Rust

![License](https://img.shields.io/badge/license-MIT-blue.svg)

This project is an implementation of the Practical Byzantine Fault Tolerance (PBFT) consensus algorithm in Rust. PBFT is a consensus algorithm designed to achieve fault tolerance in distributed systems, particularly in the presence of malicious nodes.

## Features

- **PBFT Consensus**: Implements the PBFT consensus algorithm, allowing nodes to agree on the order of transactions.

- **Actix Web Integration**: Provides a RESTful API for interacting with the PBFT network using Actix Web.

- **Asynchronous**: Utilizes asynchronous programming with Tokio for improved performance.

- **JSON Serialization**: Uses Serde and Serde JSON for message serialization and deserialization.

## Requirements

- Rust (Stable)
- Cargo (Rust's package manager)
- node.env file

## Installation

To build and run the PBFT implementation, follow these steps:

1. Clone this repository:

   ```shell
   git clone https://github.com/varshney565/PBFT.git
   cd pbft
    ```
2. Build the project:
    ```shell
    cargo build --release
    ```
3. Run the project:
    ```shell
    cargo run --release
    ```
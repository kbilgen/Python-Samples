# DNS Server Querying with Python

DNS (Domain Name System) is a system used to translate domain names into IP addresses and vice versa on the internet. DNS servers facilitate our access to websites and other internet services by performing these translations. This repository contains a Python script that demonstrates how to query DNS servers and check the NS (Name Server) records of a specific domain.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a Python script to query DNS servers and retrieve the NS records for a given domain. The script uses the `dns.resolver` module to interact with DNS servers and the `requests` module to fetch a list of DNS server IP addresses from a URL.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.x installed on your machine.
- The `dns` and `requests` Python modules installed. You can install them using the following commands:

pip install dnspython requests

## Getting Started

1. Clone this repository:
git clone https://github.com/yourusername/dns-server-query-python.git
cd dns-server-query-python


2. Install the required dependencies as mentioned in the Prerequisites section.

## Usage

1. Open the `dns_server_query.py` file.
2. Replace the `domain` variable with the domain you want to check NS records for.
3. Run the script using the following command:

python dns_server_query.py


The script will query the DNS servers for NS records of the specified domain and display the results.

## Contributing

Contributions are welcome! If you find any issues or want to add improvements, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


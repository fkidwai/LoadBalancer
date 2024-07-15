# Load Balancer Project

This project implements a basic HTTP load balancer in Go. It distributes incoming HTTP requests among a set of backend servers using a round-robin algorithm.

## Features

- **Round-robin Load Balancing**: Requests are evenly distributed among backend servers.
- **Health Checking**: Servers are checked for availability before forwarding requests.
- **Error Handling**: Basic error handling for network and server failures.


### Prerequisites

1. Make sure you have [Go](https://golang.org/dl/) installed on your machine.

### Installation

2. Clone the repository:

   ```bash
   git clone https://github.com/fkidwai/LoadBalancer.git
   cd LoadBalancer

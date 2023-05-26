# HR Management Api

## Tech Used
- **Go** (Programming Language)
- **Go Fiber** (Framework)

## Feature
Employee management: Add, Update, Delete and Retrieve employee information.

## Requirement

To run the Api, you need the following
- Golang
- MangoDB

## Installation

1. Clone this repository:
   `git clone https://github.com/subrotokumar/go-fiber-hrms`

2. Navigate to the project directory:
   `cd go-fiber-hrms`  

3. Install the dependencies

4. To start the api server, run the following command:
   ```bash
   go build main.go
   go run main.go
   ```

   The API will start running on 
   `http://localhost:3000`

## Endpoints

The following endpoints are available:
- `Get /employee` - Retrieve all employees
- `Post /employee` - Create new employees
- `Put /employee/:id` - Update an employee by ID
- `Delete /employee/:id` - Delete an employee by ID

## Configuration
- Rename the `dbnname` and `collectionName` in **main.go**
- Make sure to provide the correct MangoDB connection string

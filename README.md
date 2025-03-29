# sit323-2025-prac4p
# Task 4.1P: Calculator Microservice

This project is a simple calculator microservice built using Node.js and Express. It supports basic arithmetic operations including addition, subtraction, multiplication, and division. The goal of this task is to demonstrate how to create a basic REST API that can receive input through query parameters and return results in JSON format.

## How to Set Up and Run

1. Make sure Node.js is installed on your machine.

2. Clone the repository and open the folder in Visual Studio Code.

3. Open a terminal and run the following command to install dependencies:
   npm install

4. Start the server using:
   node server.js
   
5. Once the server is running, you can access it at:
   http://localhost:3000
 

## How It Works

The microservice accepts two input values: 'num1' and 'num2'. These are passed as query parameters in the URL. Each operation has its own endpoint:

- '/add' → Adds the numbers  
- '/subtract' → Subtracts num2 from num1  
- '/multiply' → Multiplies the numbers  
- '/divide' → Divides num1 by num2 (with division-by-zero handling)

### Example:
http://localhost:3000/add?num1=10&num2=5
This will return:
{ "result": 15 }

## Error Handling
If invalid or missing numbers are provided, the API responds with an error message. It also handles division by zero and unknown routes with appropriate responses.


GitHub repository link:  
  [https://github.com/s223060317/sit323-2025-prac4p](https://github.com/s223060317/sit323-2025-prac4p)


# AWS-LEX

🚀 Overview
This project demonstrates how to build a chatbot using Amazon Lex and AWS Lambda to fetch employee details from a CSV file stored in Amazon S3.

🛠️ Tech Stack
Amazon Lex – Conversational AI for chatbot interactions
AWS Lambda – Backend logic for processing user queries
Amazon S3 – Storage for the employee details CSV file

🎯 Features
✅ Welcome message – Greets users and prompts them for their name
✅ Personalized responses – Uses slots to capture and respond with the user’s name
✅ Employee search – Fetches employee details based on department ID
✅ AWS Lambda integration – Queries S3 data for real-time responses

🔧 Setup & Implementation
1) Create a Lex bot
   ✅ Add intents (GreetingsIntent, ReturnEmployeeName)
   ✅ Define sample utterances (e.g., "Hi", "Find employee in department 5")
   ✅ Use slots (e.g., Username, DepartmentID)
   ✅ Deploy AWS Lambda

2) Create a function in Python
   ✅ Add IAM permissions for S3 read access
   ✅ Upload the employeeDetails.csv file to S3
   ✅ Modify Lambda code to fetch department-wise employee data

3) Connect Lex to Lambda
   ✅ Assign the Lambda function to fulfill ReturnEmployeeName intent
   ✅ Test bot interactions in the Lex console

📌 Usage
 ✅ Start by saying "Hi" to receive a greeting
 ✅ Enter a Department ID to get employee details
 ✅ Get responses dynamically from the S3 dataset

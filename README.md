# Running the Express Node.js Server
# Clone the Repository: 
git clone https://github.com/r9aminu/AD320-handling-query.git

# Navigate to the Project Directory:
cd handling-query-strings

# Install Dependencies:
npm install

# Start the Server:
npm start


# Testing Query String Functionality
# Start the Server:
npm start

# Access the /get Route:
http://localhost:3000/get

# Press Enter:
After entering the URL, press the "Enter" key or click "Go" in your browser.

# View the Response:
The server will process your request and respond with a message. You should see a response in your web browser indicating that the query parameters were received and logged.
Check the Server Terminal:

Concurrently, check the terminal where you started the server. The server's terminal should display the query parameters that were logged, confirming that the server correctly received and processed the query string.
Test with Different Query Parameters:

To further test the query string functionality, repeat the process with different query parameter combinations. For example:

Access the URL: http://localhost:3000/get?color=blue&size=medium

Observe the response in your browser and check the server terminal for the logged query parameters.

# Repeat Testing as Needed:
You can continue testing the server with various query strings to ensure that it accurately parses and handles different query parameter data.
Stopping the Server:

After completing your testing, you can stop the server by pressing Ctrl + C in the terminal where the server is running. This will terminate the server process.






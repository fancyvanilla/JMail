# JMail

JMail is a simple messaging application built using Java. It allows multiple clients to send messages to other clients.

## Features

- Sending: Users can send text messages to other users.
- Receiving: Users can receive the messages from other users.
- Every user is identified by a username so you can definitely run all the tests in the same client.

## Prerequisites

To run this project, you will need:

- Java 8 or higher
- IntelliJ IDEA or any other Java IDE
- Alternatively, you can install Maven and build the project manually.

## Installation

1. Clone the repository: `git clone https://github.com/fancyvanilla/JDiscord.git`
2. Navigate to the project directory: `cd JDiscord`
3. Compile the project: `javac src/*.java`

## Usage

1. Run the server: `java src/Server`
2. In a new terminal window, run the client: `java src/Client`
3. You can run multiple clients by repeating step 2 in different terminal windows.

## Testing

To test the application, simply run the client and server applications. You should be able to send and receive messages from other clients client.
You can customize the testing in the main method of the Client class.
The testing is done using the same class `Client.java` but you can add more classes.

## Contributing

If you would like to contribute to this project, please feel free to fork the repository, create a feature branch, and then submit a pull request.

## Built With

- [Java](https://www.java.com/) - The programming language used
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) - The IDE used

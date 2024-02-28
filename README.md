
# Smart Contract: Fruit Management System
This smart contract manages a collection of fruits, allowing users to add fruits with their respective variety, ripeness, and owner's address. Additionally, users can retrieve information about fruits owned by a specific address.

# Contract Details
Contract Name: challenge
Language: Cadence (programming language for Flow blockchain)
# Structure
State Variables
fruits: A dictionary mapping addresses to fruit objects. Each fruit object contains information about a specific fruit, including its variety, ripeness, and owner.
# Structs
fruit: Represents a fruit with the following properties:
variety: A string indicating the variety of the fruit.
ripeness: An unsigned integer representing the ripeness level of the fruit.
owner: The address of the owner of the fruit.
# Functions
addFruit: Allows adding a new fruit to the collection. It takes parameters for the variety, ripeness, and owner of the fruit.

main: Retrieves information about fruits owned by a specific address.

# Transactions
transaction: A transaction that interacts with the smart contract to add a new fruit. It takes parameters for the variety, ripeness, and owner of the fruit.
Usage
# To interact with this smart contract:

Deploy the contract (challenge) to a compatible blockchain network.
Invoke the transaction function to add a new fruit, providing the variety, ripeness, and owner's address.
Optionally, call the main function, passing the owner's address to retrieve information about fruits owned by that address.
Example
# Here's an example usage scenario:

Bob wants to add a ripe apple to the collection. He invokes the transaction function with the variety "Apple", ripeness level 5, and his address.
Alice wants to check what fruits she owns. She calls the main function with her address to retrieve the list of fruits she owns.

**House Rental Smart Contract**

**Overview:**
The House Rental Smart Contract is designed to facilitate the rental process of houses through blockchain technology. It allows users to subscribe to the service and rent houses based on certain conditions.

**Features:**
1. **Subscription System:** Users can subscribe to the service by paying a subscription fee of 500 units. Once subscribed, they gain access to the rental functionality.
2. **Renting Houses:** Subscribed users can rent houses by specifying the number of houses they want to rent. They can rent up to a maximum of 5 houses at once.
3. **Ownership:** The contract is owned by an address specified during deployment, ensuring control and management of the contract's functionalities.

**Contract Variables:**
- **owner:** The address of the owner of the contract.
- **subscriptionCost:** The cost required for subscription.
- **maxContacts:** Maximum number of contacts allowed.
- **usedContacts:** Number of contacts currently used.
- **rentedHouses:** Number of houses currently rented.
- **subscribers:** Mapping to keep track of subscribed users.

**Functions:**
- **constructor:** Initializes the owner of the contract.
- **getSubscription:** Allows users to subscribe to the service by paying the subscription fee.
- **rentHouse:** Enables users to rent houses by specifying the number of houses they want to rent.

**Error Handling:**
- The contract ensures that users provide the correct amount for subscription.
- It prevents users from subscribing multiple times.
- Users cannot rent more than 5 houses at once.

**License:**
This smart contract is licensed under the MIT License, allowing users to freely use, modify, and distribute the code.

**Author**

shashank jk 

shashjk5@gmail.com

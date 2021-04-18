# Homework-19
Blockchain with Python

To begin we first need to download the hd-wallet tool.

In this homework we made two sorts of transactions, one for bitcoin and another one for Ethereum. the goal was to succesfully code out some way to send the testnet coins and look at the transaction and get a better feeling on how one can check to see their crypto transactions through pyton.

![image](https://user-images.githubusercontent.com/71734654/115148219-372e9a80-a024-11eb-9b12-fa1147fc09cb.png)

Above is the code for the Bitcoin transaction. The main thing that helps this assingnment get moving is the hd wallet derive tool. This tool allows us to use one wallet and  within that wallet pass different types of keys so addresses can be read, multiple transactions can be performed within(sending/recieving coin).

The code is built with web3 imports and functions that take in the private key of an address, and take in parametes of the sender and the recipeint. You create a creat_transaction function that takes in parametes of the sender, who the coin is going to, and the amount thats being sent. Then you create the send function with a few of the same parameters. For the final step you use the functions and pass in the parameters and then you should recieve a notice on this website that your transaction has gone through. It should look something like this.
![image](https://user-images.githubusercontent.com/71734654/115148647-2ed75f00-a026-11eb-9805-09668c709c08.png)

The transaction for the ethereum con is pretty similar to to this one.
![image](https://user-images.githubusercontent.com/71734654/115148703-6940fc00-a026-11eb-8d73-44b4d685428c.png)
![image](https://user-images.githubusercontent.com/71734654/115148721-7d84f900-a026-11eb-9206-159267a14c85.png)

You can see the similarities. The only differences are the address types!

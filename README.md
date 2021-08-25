## HD Wallet ##
![image](/images19/newtons-coin-cradle.jpg)

# The objective is to build a HD wallet and run transactions.
# First step is to install HDWallet Derive and test we can run ./derive:

![image](/images19/Picture1.png)


Validate directory for wallet as below: 
![image](/images19/Picture2.png)


# We are ready now to create the python code, constants.py and wallet.py (wallet.ipynb located in directory).

The following functions were created:
![image](/images19/Picture3.png)

Priv_key_to_account function: This function will convert the privkey string in a child key to an account object that bit or web3.py can use to transaction

![image](/images19/Picture4.png)

Create_tx: This function will create the raw, unsigned transaction that contains all metadata needed to transact
Send_tx: This function will call create_tx, sign the transaction, then send it to the designated network.

![image](/images19/Picture5.png)

# We are ready now to send some transaction using BTCTEST and ETH

# BTCTEST

# Select the first address and fund it
![image](/images19/Picture6.png)

Then check the balance:
![image](h/images19/Picture7.png)


# Next we choose a second BTCtest account from our list to send tnx to:
![image](/images19/Picture8.png)

Now use the "send_trx" function to send a transaction from first account to the second account.
![image](/images19/Picture9.png)

# Confirm Tnx was sent successfully:
![image](/images19/Picture10.png)

# Next we test ETH: 
![image](/images19/Picture11.png)

For this excercise we interacted directly with Ganache for ETH 

From address:
![image](/images19/Picture12.png)
To address: 
![image](/images19/Picture13.png)
or ETH we added private key manually from Ganache:
![image](/images19/Picture14.png)

Then we ran our function and checked to verify the balance for the first account to ensure funding:

![image](/images19/Picture15.png)

Sending Tnx From address 1 to address 2:

![image](/images19/Picture16.png)

# Confirm Tnx was sent successfully:

![image](/images19/Picture17.png)

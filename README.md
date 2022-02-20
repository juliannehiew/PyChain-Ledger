# PyChain-Ledger

![PyChain Ledger](Images/application-image.png)

You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

You’ll make the following updates to the provided Python file for this assignment, which already contains the basic `PyChain` ledger structure that you created throughout the module:

1. Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Modify the existing `Block` data class to store `Record` data.

3. Add Relevant User Inputs to the Streamlit interface.

4. Test the PyChain Ledger by Storing Records.

---


## PyChain Ledger Result 

## Streamlit application


## ![Streamlit screenshot](https://github.com/juliannehiew/PyChain-Ledger/blob/main/Images/PyChain%20stored%20records.JPG)


Correspondingly, values for the sender, receiver, and amount are entered as above.  Once 'Add Block' button is clicked, the block is stored in the ledger.  This step is repeated several times to store several blocks in the ledger.  

Besides this, block contents and hashes are located in the Streamlit drop-down menu on the left side of the screen.  This provides detail of blockchain that consists of multiple blocks.

To conclude, the chain is being validated as 'True'.  Therefore, the PyChain Ledger is successful by storing these records.

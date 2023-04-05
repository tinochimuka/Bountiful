# Step-By-Step Instructions to set up bountiful:

## 1: Create Contract
In an empty folder, open Visual Studio Code and creat an empty folder called client. This is where all our front-end code will reside.
![Screenshot (27)](https://user-images.githubusercontent.com/129856164/229991420-1698fcbb-999b-415b-abe7-372fa7571414.png)

You can then proceed to open the terminal, (without cd into client) and run the following command:
-- npx thirdweb@create --contract
This will initiate the build process as thirdweb constructs the necessary files and dependencies needed to build and deploy a smart contract easily. You should see something like this:
![Screenshot (29)](https://user-images.githubusercontent.com/129856164/229991828-55b0a8ce-7c51-4242-818f-074d0149a624.png)
![Screenshot (30)](https://user-images.githubusercontent.com/129856164/229991827-d205df81-a30d-49b8-b152-c6e6ec50f6c3.png)

For the first option, name your proect web3
![Screenshot (30)](https://user-images.githubusercontent.com/129856164/229992379-7c7e4a33-e010-488b-a904-029d0ead1837.png)


For the second option, select HardHat
![Screenshot (31)](https://user-images.githubusercontent.com/129856164/229992394-2739015b-05d5-4daf-9389-39f4d4056d47.png)


For the third option, name your contract anything you like, such as your company name or the purpose of the contract, in this case crowdfunding
![Screenshot (32)](https://user-images.githubusercontent.com/129856164/229992558-5779fcad-f1ba-4b3a-a2db-d83bb3b569ca.png)

For the final option, select EmptyContract, and let thirdweb start building your contract!
![Screenshot (33)](https://user-images.githubusercontent.com/129856164/229992691-91cd9db0-b94a-4215-a723-5e012695570b.png)

<br/>
## 2: Create MetaMask Wallet
This wallet is a crypt based wallet that serves as a wallet on any blockchain platform. This is what we will use to connect to our contract and our frontend, 
make transactions and deploy our contracts. 
To do so, visit: http://metamask.io/ and click the 'Add to Chrome Button'
![Screenshot (35)](https://user-images.githubusercontent.com/129856164/229993787-61671998-4d95-4c0c-9392-0e78a869f1d0.png)

After this step, follow the instructions to create a new account until you arrive at your main account page:
![Screenshot (38)](https://user-images.githubusercontent.com/129856164/229993933-1f90545e-a592-4a21-b8fa-9391a858309c.png)

Once your account has been set up, click on the top right bar where it says etherium mainnnet, select the drop down, select 'show/hide test networks' and set visibility 
for testnetworks to be on. This will allow us to connect to the Goerli tesnet and transact with GoerliEther, a testnet version of an etherium token.

![Screenshot (39)](https://user-images.githubusercontent.com/129856164/229994504-9bd251da-aa0f-4f64-991a-320465c62d98.png)

**Make sure to pin the metamask wallet to your browser toolbar for ease of access:**


Once this is complete, you should see a little orange fox at the top of your google chrome toolbar, and you can click on this to connect to Goerli. 
Select the button written 'Etherium Mainnet' and change the mainnet to the Goerli Testnet. (Upon production deployment, just do this in reverse).
You should see the results shown below:
![Screenshot (41)](https://user-images.githubusercontent.com/129856164/229995161-4d554043-3168-4174-bf4a-8787669b0bc1.png)

<br/>


## 3: Add Some GoerliETH to your wallet:
At the top of your wallet, youll see an address, this is your metamask wallet address. Click to copy this to your keyboard:
![Screenshot (44)](https://user-images.githubusercontent.com/129856164/229995713-bf00da64-c236-41a6-830f-754c7a080357.png)

Once complete, go to https://goerli-faucet.pk910.de/ to start mining some crypto! This faucet requires you to perform mining in return for some goerli tokens. 
Pass the Captcha test and past the copied address into the 'Address' bar and click start mining. This uses your computers processing resources to create
verify hashes for other developers in return for some Etherium. You can mine all you want for up to 5 hours, but the minimum claim reward is 0.001 GoerliETH
which takes at most 5 minutes of mining on a slow computer. Average testnets cost 0.05 GoerliETH (45 minutes - hour of mining) during non-peak times and around 
0.1 GoerliETH at peak times. 
![Screenshot (46)](https://user-images.githubusercontent.com/129856164/229996740-709969f5-19af-4d2b-a165-e34f724d80d5.png)
![Screenshot (47)](https://user-images.githubusercontent.com/129856164/229996820-65a10dc8-5f9a-4b1c-94fa-c63fcf279d3d.png)

**Leave this Process to run for a few hours**

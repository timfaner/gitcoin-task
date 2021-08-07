### Task7 sumbit

Submission creator: timfaner



#### 1 screenshot or video runing on Godwoken



Videolink: https://www.youtube.com/watch?v=j7g6zDxvNlI

![screenshot](screenshot.png)



#### 2 Github repo url

https://github.com/timfaner/ckbet



#### 3 Contract address;TxHash;ABI

##### Contract address

0x604eD4c60b6d0846e2E403aDa42FE5e3De4d4B8e



##### Depoly transcation hash

0xd08e874d2f54aa7abaa7ef18c1ddaa2fa316bb8bb51a9dbab5caef874453a5aa

##### ABI

```
  "abi": [
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_minBet",
          "type": "uint256"
        },
        {
          "internalType": "uint256",
          "name": "_houseEdge",
          "type": "uint256"
        }
      ],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "anonymous": false,
      "inputs": [
        {
          "indexed": false,
          "internalType": "bool",
          "name": "_status",
          "type": "bool"
        },
        {
          "indexed": false,
          "internalType": "uint256",
          "name": "_amount",
          "type": "uint256"
        }
      ],
      "name": "Won",
      "type": "event"
    },
    {
      "inputs": [],
      "name": "kill",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "stateMutability": "payable",
      "type": "receive"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_number",
          "type": "uint256"
        }
      ],
      "name": "bet",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "checkContractBalance",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_amount",
          "type": "uint256"
        }
      ],
      "name": "withDraw",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```




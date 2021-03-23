# DLT lab 1
```
Roman Solovev
Igor Krasheninnikov
Mariia Charikova
```
Files:
* `lab1.html` - JavaScript implementation of SCC interface to interact with contract. Available actions: check balance, get 1 coin (only works if you are 30 meters or less from SC), transfer tokens and check total supply
* `Lab1.sol` - Solidity implementation of contract, deployed at Ropsten network (`0x36894816d2D5153FD7D076AFca0370AFFcFDdcc8`). 

Example workflow:  
1. Check initial balance:  
![](https://i.imgur.com/hIENHtE.png)
2. Request 1 token, fail because you are far from SC:  
![](https://i.imgur.com/kr0C6oI.png)
3. Go near SC and try again:  
![](https://i.imgur.com/OziDQHH.png)  
4. Transaction is created:  
![](https://i.imgur.com/7Upsbol.png)
5. Check balance after transaction is completed:  
![](https://i.imgur.com/hNecgGc.png)
6. Decide that you dont need this token and send it to your friend:  
![](https://i.imgur.com/hjSBIn5.png)
7. Confirm transaction:  
![](https://i.imgur.com/sFihwnV.png)
8. Check balance again - you have 0:  
![](https://i.imgur.com/Kksrtfn.png)
9. But your friend has one!:  
![](https://i.imgur.com/qW1XEpS.png)
10. You can also check total supply, if you want:  
![](https://i.imgur.com/zzKoWmx.png)





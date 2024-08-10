# Rivalz-Ai-Node-Run-Full-Guide

## Rivalz Ai V1 Client Node Run

![gsg](https://github.com/user-attachments/assets/d2cb8005-b0f4-4dec-bd62-dc8169f86035)

1. Go:- https://tinyurl.com/38ht9d5a

   👉Connect Wallet > Go To My Client V1 > Click Download RClIENT (according to ur operating system)
   
   👉Then Open File > Put ur Metamask Address (put same add u used in website also) > Then Give Storage > Then Start the Node > Then check ur all Status in Dashboard

 ![Put ur Address](https://github.com/user-attachments/assets/b58dd6eb-3874-47fa-9e23-b9edf1eecfb6)

## Rivalz Ai V2 Client Node Run

![Screenshot 2024-08-10 093026](https://github.com/user-attachments/assets/706a548e-3dc3-4427-bbe5-7087a84f3d9f)

1️⃣ Install WSL - https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command

2️⃣ Put One by One Command & Run in WSL
```
sudo apt update
```
```
curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
```
```
sudo apt install -y nodejs
```

3️⃣ Check NodeJs & NPM version it's showing or not (If not Showing then install again)
```
node -v
```
```
npm -v
```

4️⃣ Add all 126 Packages
Run Only One Command if 1st one is worked then don't used 2nd one
```
npm i -g rivalz-node-cli
```
OR
```
sudo npm i -g rivalz-node-cli
```

5️⃣ Run Rivalz V2
```
rivalz run
```
👉Put ur Metamask Address (put same add u used in website also & V1) 
👉Then Select ur Drive(SSD/HDD) > Then Give Storage 
👉Then Validate & Synced Succesfully > Then check ur all Status in Dashboard in (My Client V2)


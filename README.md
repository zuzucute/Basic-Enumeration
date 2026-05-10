# Basic-Enumeration

Lab Setup
* Attacker : Kali Linux
* Attacker IP :  192.168.56.104
* Target : Metasploitable 2
* Target IP : 192.168.56.105

Challenge 1
```
nbtscan -a 192.168.56.105
```
<img width="1062" height="868" alt="image" src="https://github.com/user-attachments/assets/5b81613e-fe41-4f41-ae16-b8278a46152a" />


Challenge 2
```
nmap -F 192.168.56.105
```
<img width="578" height="478" alt="Screenshot 2026-05-10 205945" src="https://github.com/user-attachments/assets/4d33fbaf-2ad1-4595-9cff-e9b1ca44c701" />

Challenge 3 
```
nslookup google.com
```
<img width="302" height="180" alt="image" src="https://github.com/user-attachments/assets/92acc597-d2ea-4492-8af3-1f05554ae1a7" />
```
dig ANY google.com
```
<img width="930" height="467" alt="image" src="https://github.com/user-attachments/assets/0ba1489c-e69a-4504-977f-1be1edecd2da" />
```
dig MX google.com
```
<img width="575" height="353" alt="image" src="https://github.com/user-attachments/assets/ad7528e0-7db9-48af-8ae6-7dda8f425aaa" />


Challenge 4 
```
nc 192.168.56.105
```
<img width="227" height="82" alt="image" src="https://github.com/user-attachments/assets/2d5f778f-5bfa-420f-887a-6311125a899a" />

Challenge 5
```
ftp 192.168.56.105
```
```
ls -la
```
<img width="503" height="301" alt="image" src="https://github.com/user-attachments/assets/b2c3b090-a1ce-46ec-873f-302eab2e7dcf" />

Challenge 6
```
nmap -sV 192.168.56.105
```
<img width="1022" height="587" alt="image" src="https://github.com/user-attachments/assets/d462a599-eb76-4c6d-acb9-bd980adfaf86" />

Challenge 7
```
nmap -O 192.168.56.105
```
<img width="772" height="642" alt="image" src="https://github.com/user-attachments/assets/2e448174-7c6f-45e2-ac11-a5a509d63306" />

Challenge 8
```
rpcinfo -p 192.168.56.105
```
<img width="381" height="425" alt="image" src="https://github.com/user-attachments/assets/2d7b2702-7a9e-4a26-8539-89e14c3be52a" />

Challenge 9
```
nc 192.168.56.105 25
```
<img width="442" height="67" alt="image" src="https://github.com/user-attachments/assets/ae10655f-aeba-420b-a8fb-eb864b1956f6" />

Challenge 10
```
enum4linux -a 192.168.56.105
```
<img width="931" height="202" alt="image" src="https://github.com/user-attachments/assets/093aa2a3-6c07-444e-bcae-9af3d8a9c86c" />

<img width="927" height="377" alt="Screenshot 2026-05-10 232333" src="https://github.com/user-attachments/assets/97027b6a-cc28-4d34-b2fb-4c0b4eacfd0a" />

<img width="936" height="702" alt="image" src="https://github.com/user-attachments/assets/883c1ad2-59bc-4996-b19c-377a7be22e5a" />


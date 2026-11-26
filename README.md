# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1920" height="923" alt="image" src="https://github.com/user-attachments/assets/42fdf116-a800-480d-a464-8cb9547a5ee6" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1920" height="923" alt="image-1" src="https://github.com/user-attachments/assets/48565247-6e4a-4a03-b20b-8e633f0509c8" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1920" height="923" alt="image-2" src="https://github.com/user-attachments/assets/68e8df0c-ba51-459b-b0ee-a7091b8254d0" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1248" height="482" alt="image-3" src="https://github.com/user-attachments/assets/c886803d-2af3-4f88-beeb-047b2cf84a0b" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="1020" height="606" alt="image-4" src="https://github.com/user-attachments/assets/3685a97b-e8da-4900-a9e4-a52d0cde77ff" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="1238" height="596" alt="image-5" src="https://github.com/user-attachments/assets/ab39c486-4213-463e-9ed2-13076125af83" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1920" height="923" alt="image-6" src="https://github.com/user-attachments/assets/003be5ab-10de-4ac1-b5a9-3ff3563ac259" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1055" height="1024" alt="f657705f-ac2e-403a-a8fe-13097d99ec70" src="https://github.com/user-attachments/assets/08246153-bb99-472e-bc85-a52c03e6a338" />



SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1894" height="600" alt="image-7" src="https://github.com/user-attachments/assets/1b2f263a-9365-4a7d-8600-a7b8a7fab8b3" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT


<img width="1488" height="716" alt="ab409263-ac6b-4e3e-b27f-ceeea30be1ff" src="https://github.com/user-attachments/assets/bea4007b-fedd-44cc-afa1-b67270fdc372" />










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

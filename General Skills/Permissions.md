# Challenge: Permissions

- **Points:** 100
- **Status:** Solved

## Description
Can you read files in the root file?  
The system admin has provisioned an account for you on the main server  
Can you login and read the root file?  

## Hints
1. What permissions do you have?

## Requirements to do Challenge
puTTy (optional) - [Link to download puTTy](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)


## Important information I learnt and researched about challenge
**What is ssh** 
SSH also known as Secure Shell or Secure Socket Shell is a network communication protocol that enables two  computers to communicate and share data. An inherent feature of ssh is that the communication between the two  computers is encrypted meaning that it is suitable for use on insecure networks. SSH is often used to "login"  and perform operations on remote computers but it may also be used for transferring data[[1]](https://www.ucl.ac.uk/isd/what-ssh-and-how-do-i-use-it).

**When and Why use ssh**
SSH connections have been used to secure many different types of communications between a local machine and a  remote host, including secure remote access to resources, remote execution of commands, delivery of software   patches, and updates and other administrative or management tasks [[2]](https://www.techtarget.com/searchsecurity/definition/Secure-Shell) .

In addition to creating a secure channel between local and remote computers, SSH is used to manage routers,   server hardware, virtualization platforms, operating systems, and inside systems management and file transfer applications [[2]](https://www.techtarget.com/searchsecurity/definition/Secure-Shell) .

Secure Shell is used to connect to servers, make changes, perform uploads and exit, either using tools or  directly through the terminal. SSH keys can be employed to automate access to servers and often are used in   scripts, backup systems and configuration management tools [[2]](https://www.techtarget.com/searchsecurity/definition/Secure-Shell) .

In this challenge The ssh connection enables the user to remotely access the servers and perform some limited  actions they have permission to execute.  
You can use the webshell or puTTy to make the ssh connection and do this challenge.  

## Steps
1. **Step One: Make an ssh connection to the remote computer.**
**If using webshell**:
<pre>
ssh [options] UserName@SSHserver.example.com
</pre>
Replace UserName with your actual username on the remote server  
SSHserver.example.com with the appropriate hostname or IP address of the remote server you want to connect to.  
[options]: Optional command-line options that modify the behavior of the SSH command. Some common options include:  
-p PORT: Specify a custom port number for the SSH connection.  
-i IDENTITY_FILE: Specify the path to a private key file for authentication.  
-l LOGIN_NAME: Specify the login username (equivalent to Username@ part).  
-v: Increase verbosity for debugging.

**If using puTTy**:
![Make an ssh connection using puTTy input Host Name or IP address and Port number ](https://github.com/poni-henry/picoCTF_2023_WriteUps/blob/main/Images/putty.png)  
2. Step Two  
3. Step Three  
4. Step Four  
5. Step Five  

---

**Remember:** Each flag is unique and the flag you obtain from solving this challenge will not be the same flag you get when you follow these steps.


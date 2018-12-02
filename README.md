# AI-DevCloud
### Linux and Mac
1. DownLoad the Linux Access key
2. Add the to the ～/.ssh.config
      
       >Host `the service_name`
       >User `the account name`
       >IndentityFile `the access key`
       >ProxyCommand ssh -T -i `the access key`  account@ip.address

3. chmod 600 `access key`
4. chmod 600 ~/.ssh/config



### log in 
ssh `the service_name`

### Transferring Files
  
  >scp /path/to/local/file `the service_name`:/path/to/romate/directory/
  
  


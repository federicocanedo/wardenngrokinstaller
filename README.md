# Warden Ngrok Installer
Installs ngrok on a warden magento 2 installation

## How to use

- ./ngrokinstaller -d domain [-n ngrok-token | -r ]

  Examples:
  
  ./ngrokinstaller -d test2.4.4 -n ngrok-token
  
  ./ngrokinstaller -d test2.4.4 -r
             
   
- Arguments:
 
  -d : domain of the magento installation
  
  -n ngrok-token : installs ngrok on the installation mentioned above with the token provided
  
  -r : removes ngrok on the installation mentioned above, sets it back to https://app.domain.test/

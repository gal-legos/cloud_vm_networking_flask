
# Flask on Cloud VM (Assignment 2)

## Student Info
- Name: Emily Gallegos
- Cloud Provider: GCP

## Video recording: 
- Zoom [video](https://www.canva.com/design/DAG1041V-DM/74Hn-27SKV5TqouVUFQrfw/edit?utm_content=DAG1041V-DM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) 

## Steps
### 1. VM Creation
![VM_Creation_1](vm_networking_screenshots/vm_creation.png)
![VM_creation_2](vm_networking_screenshots/vm_creation_2.png)

### 2. Networking (Port 5003 Open)
In order for port 5003 to be used, the 'http' and 'https' boxes needed to be selected in the networking configuration when initially creating the VM instance. 
![networking_http](vm_networking_screenshots/http_https_allow.png)

In addition to the adjusting the network configurations, a firewall rule needs to be set up that allows for port 5003 to be open 
![networking_firewall](vm_networking_screenshots/firewall_rule_creation.png)

### 3. OS Update + Python Install
'sudo apt update && sudo apt upgrade -y' was used to update and upgrade the operating system.
![OS_update](vm_networking_screenshots/upgrade_update.png)

'sudo apt install git python3 python3-pip python3.13-venv -y' was used to install python and some other dependencies necessary to properly run the web app
![install_python](vm_networking_screenshots/install_pip_python_git_venv.png)

### 4. Flask App Running
![running_app](vm_networking_screenshots/flask_app_running.png)
![browser_running](vm_networking_screenshots/running_application.png)

### 5. Public IP Access
URL: http://104.154.233.167:5003  
![public_ip](vm_networking_screenshots/publiv_ip_address.png)



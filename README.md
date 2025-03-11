# Deploying Sophos firewall in Azure LAB

## Objective

The main objective of deploying the Sophos Firewall in Azure is to secure cloud workloads, control network traffic, and establish a secure connection between on-premises users and Azure-hosted resources. This setup ensures advanced threat protection, traffic filtering, VPN connectivity, and network segmentation within an Azure cloud environment.

### Job Skills Learned

- Cloud Networking & Security
- Deploying Sophos XG/XGS firewall in Azure
-  Configuring WAN and LAN interfaces
- Network Segmentation & Routing
- Cybersecurity & Compliance


### Tools Used

- Microsoft Azure Portal
- Sophos XGS Firewall v21.0 (virtual instance) 
- Access to the Sophos Central Management Portal
- SFOS 21.0 Web Interface (GUI)
- SFOS 21.0 Command Line Interface (CLI)
- Control Center Dashboard: Built-in monitoring tool for real-time traffic and event analysis.


*Ref 1: Network Diagram*
![image](https://github.com/user-attachments/assets/f1fd83a1-fd8f-4349-b471-1d0a401d2855)

 




## CONFIGURATION STEPS
![image](https://github.com/user-attachments/assets/dedc349e-fef5-44ab-9ef8-3a4a6fbbc882)
 
Create Sophos Firewall
 ![image](https://github.com/user-attachments/assets/c652e38f-4dd8-4426-be7b-c1450a86495c)

Instance details and create virtual network
![image](https://github.com/user-attachments/assets/fc323f35-1150-42c8-bf34-6a9fd694cd8b)

 
Create public IP
![image](https://github.com/user-attachments/assets/a2700e89-4623-4536-8cf2-0c83ebef8e2c)
![image](https://github.com/user-attachments/assets/562940f4-f752-465d-b771-aa817e858d89)
 
 
Our Sophos is running and created in Azure
![image](https://github.com/user-attachments/assets/5ab7fca2-eaa0-47f2-a622-234f5a297a52)
![image](https://github.com/user-attachments/assets/1bb50949-40ce-4426-b5c5-a7dede70cd02)
 
 
Now we can access the firewall using it’s Public IP address
![image](https://github.com/user-attachments/assets/b01b9e53-2b05-4051-ad4f-bae14f72b87a)
 
We can also use it’s DNS name
![image](https://github.com/user-attachments/assets/6e7cca43-4566-4a36-b488-9ef23b9265d9)
![image](https://github.com/user-attachments/assets/e4e78dd2-d989-443f-a003-9901906903ac)


 
 


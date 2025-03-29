# cst8918-lab3
Lab 3 DevOps Security and Compliance wats0358

1. Create an Azure VM for a Ubuntu Server (18.04 or higher)
![1](screenshots/1_AzureVM.png)

2. Enable Port 3000 for Grafana in our VM's network settings

![2](screenshots/2_GrafanaInbound.png)

3. Start and enable the grafana server in the terminal 

![3](screenshots/3_GrafanaStart.png)

4. Verify that the grafana server is running by navigating to the IP

![4](screenshots/4_GrafanaLogin.png)

5. Enable managed identity in the VM's Security settings

![5](screenshots/5_identity.png)

6. Assign Monitor Reader and Reader roles in role assignment

![6](screenshots/6_RoleAssignments.png)

7. Edit /etc/grafana/grafana.ini in the Grafana VM to have managed identity true
![7](screenshots/8_managed_identity_enabled.png)

8. Create the log analytics workspace for Grafana in Azure
![8](screenshots/7_LogAnalytics.png)

9. In Grafana, add the azure monitor data source and authenticate using managed identity
![9](screenshots/9_GrafanaDataSource.png)

10. Create a dashboard and choose Azure Monitor as the data source
![10](screenshots/10_Dashboard.png)



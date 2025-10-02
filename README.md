# Monitoring_task-using-Netdata
Install Netdata, visualize system and app performance metrics.

Following steps taken to complete the task:

**--->** Launched the EC2 instance and installed **Docker** and to integrate with **Netdata** provided command **(chmod 777 ///var/run/docker.sock)**

Using the command installed Netdata with Docker ( docker run -d --name=netdata -p 19999:19999 netdata/netdata) and after installing verified Docker Images & Containers and did some playaround to confirm that it is working fine.

<img width="762" height="82" alt="Cont is created" src="https://github.com/user-attachments/assets/b7012540-48a7-408a-9189-059d3417f206" />

<img width="760" height="172" alt="Images   containers list" src="https://github.com/user-attachments/assets/c0ff25e4-e485-4219-9295-05a4fa55fc6e" />

**--->**Using Netdata default port **19999** with server PUBLIC IP opened the Monitoring tool

<img width="946" height="395" alt="Dashboard of net data" src="https://github.com/user-attachments/assets/37d8ca16-f1a1-4b32-b45e-b5eb1a7ee3d8" />

**--->** Monitored System Resources Using Netdata below are the snapshots:

<img width="536" height="50" alt="Log information" src="https://github.com/user-attachments/assets/af15a4da-9462-4c6f-a442-9a95493eebb2" />

<img width="860" height="315" alt="CPU usage" src="https://github.com/user-attachments/assets/09f39faa-2af7-4fae-8923-19a89fb48884" />

<img width="858" height="329" alt="Disk usage" src="https://github.com/user-attachments/assets/b24d1d47-b332-4191-b923-c666a80f251f" />

<img width="875" height="315" alt="Docker details" src="https://github.com/user-attachments/assets/14fe836d-6142-4932-88dc-25a7a74a7470" />

<img width="701" height="269" alt="Ram Usage" src="https://github.com/user-attachments/assets/30846804-5545-434b-bc45-48e9492a8cbf" />












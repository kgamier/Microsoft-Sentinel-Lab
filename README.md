# Microsoft-Sentinel-Lab

**In this lab, a PowerShell script was executed on a remote desktop with a disabled firewall, in this case, an Azure Virtual Machine. The script used an API from a third-party  utility, app.ipgeolocation.io, to obtain the metadata for failed RDP attempts executed by attackers from around the world. This log data was compiled into a text file in the remote desktop's ProgramData folder, which was exported and made into a Log Analytics Workspace table. A log query was then made in Microsoft Sentinel which was used to plot the data from the text file.**

**Incoming attacks on remote desktop**
![RDP failed attempts](https://github.com/user-attachments/assets/eee202fd-3bbb-4c5d-a52a-a8fccbeee75d) 

**Plotted Sentinel Heatmap using attacker log metadata**
![rdp_heatmap](https://github.com/user-attachments/assets/46950539-3f23-49bb-9d70-9055b18a99bb)

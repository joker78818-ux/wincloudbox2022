# Cloud PC - Windows Server 2022  
**Cloud PC - Have a server at absolutely no cost! 💻✨**

Welcome to your very own personal Cloud PC running **Windows Server 2022**! This is like having a powerful server in the cloud — ready to use, fully configured, and accessible from anywhere via RDP. No downloads, no expensive hardware, no setup headaches — just your server in the cloud, ready to work or play.

💡 **Why Cloud PC Server 2022?**  
Ever needed a fresh server environment for testing, development, or running Windows-only server software? This workflow gives you a **Server 2022 Cloud PC** without owning physical hardware. It's ideal for developers, IT professionals, or anyone needing a secure, high-performance Windows server environment in the cloud.

⚙️ **Server Specs**  
Your personal cloud server is configured with realistic, high-end specs for smooth operation:  

- **CPU:** AMD EPYC  
- **vCPUs:** 2–4 cores  
- **RAM:** 8–16 GB  
- **Storage:** 256 GB primary SSD (additional D: drive optional)  
- **Drivers:** Fully preinstalled for Windows Server 2022  
- **Internet:** 3–4 Gbps, perfect for remote tasks, downloads, and server workloads  

🖥️ **What You Get**  

When you launch the workflow, your Server 2022 Cloud PC will:  

- Prepare a personal user account  
  - User: `CloudPCUSER`  
  - Password: `WindowsCloudPC#2025`  
  - Added to **Administrators** and **Remote Desktop Users** groups  
- Enable Remote Desktop (RDP)  
- Auto-login for seamless access  
- Firewall disabled for unrestricted connectivity  
- Keep-alive functionality  
  - Cloud PC stays alive for 5 hours  
  - Logs connection details for easy access  

🚀 **How It Works**  

1. Trigger the workflow manually in GitHub Actions.  
2. Enter the friendly server name and required secrets (if any).  
3. The workflow will:  
   - Rename your server to the chosen name  
   - Create the **CloudPCUSER** account with admin privileges  
   - Enable RDP for remote access  
   - Keep your server alive and accessible for 5 hours  

🔑 **Login & Access**  

- User: `CloudPCUSER`  
- Password: `WindowsCloudPC#2025`  
- Access: Connect via RDP using the server name or IP displayed in workflow logs  

💬 **Tips & Tricks**  

- Want a fresh Server 2022 Cloud PC after 5 hours? Relaunch the workflow — a new server will be created.  
- Change the server name when starting the workflow to make it unique.  
- Use the logs to quickly grab your server's IP or connection info.  
- Ideal for testing, running builds, or hosting temporary server applications.  

🎉 **Final Words**  
Your Windows Server 2022 Cloud PC is your personal cloud server, ready anywhere, anytime. No cost, no setup, full admin access — just your server in the cloud. Enjoy fast networking, a clean Windows environment, and full control over your server for 5 hours.  

💻 **Looking for the Windows 2025 desktop version?**  
Check out this repo: [wincloudbox](https://github.com/danielsimpledani-rgb/wincloudbox)

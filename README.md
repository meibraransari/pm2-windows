---
Created: 2024-08-07T10:21:09+05:30
Updated: 2024-08-07T12:09:05+05:30
Maintainer: Ibrar Ansari
---
# PM2 WINDOWS STARTUP 

Make PM2 automatically start on Windows startup

## Installation
```
npm install pm2 -g
npm install pm2-windows-startup -g
```
## Enable on Reboot
```
pm2-startup install
pm2-startup enable
```
## Register Job
```
pm2 start app.js --name "my-app1"
or
pm2 start npm --name "my-app" -- run dev
or
pm2 start "npm run dev" --name my-app
```
PM2 will now automatically revive the saved processes on startup. To save the current list of processes execute:
```
pm2 startup
pm2 save
```
## Check Registered Jobs
```
pm2 list
```
## Check logs
```
pm2 logs <JOB_ID/JOB_Name>
```
## PM2 Cheat-Sheet
[Click on this link to see PM2-Cheat-Sheet for more details....](https://github.com/meibraransari/pm2-cheatsheet)

---
### 💼 Connect with me 👇👇 😊

- 🔥 [**Youtube**](https://www.youtube.com/@DevOpsinAction?sub_confirmation=1)
- ✍ [**Blog**](https://ibraransari.blogspot.com/)
- 💼 [**LinkedIn**](https://www.linkedin.com/in/ansariibrar/)
- 👨‍💻 [**Github**](https://github.com/meibraransari?tab=repositories)
- 💬 [**Telegram**](https://t.me/DevOpsinActionTelegram)
- 🐳 [**Docker**](https://hub.docker.com/u/ibraransaridocker)

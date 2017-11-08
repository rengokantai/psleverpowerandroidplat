# psleverpowerandroidplat
## 5. Using Alarms to Schedule Time-sensitive Tasks
### 3 Alarm Manager
alarm manager
- not tied to the lifetime of your app
```
Context.getSystemService
```
Commonly handled by broadcast receiver
- Often uses manifest declared receiver
- Allows work to be performed even if app not currently running.

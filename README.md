# Dria-Node-Full-Guide



**Install Ollama from here Copy this link and open in Any Browser (Choose Your OS)**

```
https://ollama.com/download/linux
```
  
 Verify Version 
  ```
  ollama --version
  ```

**Dependencies for WINDOWS & LINUX & VPS**
```
sudo apt update
sudo apt upgrade -y
```

**Create New screen For VPS Only**
```
apt install screen -y
```
```
screen -S dria
```



# Installation Of Dria Launcher

Open The Powershell in Administrator mode **Windows only**
```
powershell -c "irm https://dria.co/launcher.ps1 | iex"
```
🔺Restart Your powershell if you are using Window (Important)


**For VPS / Linux**

```
 curl -fsSL https://dria.co/launcher | bash 
```


# Run the Node with your Burner Metamask wallet private Key without "0x"


For VPS / Linux
```
dkn-compute-launcher start
```
**Windows or Command Prompt (CMD)**
```
dkn-compute-launcher.exe start
```

Choose a model according to your specs and put yor metamask key as shown in the video guide.


You Can check Your Node status and earned points from here👇

https://dria.co/edge-ai

# Fill This Form to Get Node keeper Role in Discord👇

https://form.typeform.com/to/Eav42hR3?typeform-source=www.google.com



## For Next Day Run This Command 

#1 Open WSL and Put this Command **(VPS / Linux)**
```
dkn-compute-launcher start
```
**Windows or Command Prompt (CMD)**
```
dkn-compute-launcher.exe start
```


# Optional Update Node (If you are Facing any Issues)

# Change Model 
```
dkn-compute-launcher settings
```
# Remove Dria (VPS/Linux)
```
rm -rf ~/.dria
```
**Windows or Command Prompt (CMD)**
```
rd /s /q "%USERPROFILE%\.dria"
```

👉 Join TG for more Updates: https://t.me/kind_cr

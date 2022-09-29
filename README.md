# Ngrok :computer::heavy_minus_sign::computer:

Ngrok es un sevicio que te permite abrir un puerto en Internet sin necesidad de tocar la configuración del router.

### ***¿Como se descarga Ngrok?***

**¡Para ello es importante saber que tenemos que tener permisos de superuser!**, para ello usaremos el siguente comando, ```sudo su``` e introduciremos nuestra contraseña de superuser.

### ***Ngrok para Linux***

**Existen dos formas de instalar Ngrok:**

- ***Vía Snap***
1. Primero instalaremos Snap usando el siguiente comando: ```sudo apt install snapd -y```
2. Usaremos Snap para instalar Ngrok, para ello usaremos el siguiente comando: ```snap install ngrok```

- ***Vía Curl***
1. Primero instalaremos Curl usando el siguiente comando: ```sudo apt install curl -y```
2. Usaremos Curl para instalar Ngrok, para ello usaremos el siguiente comando: ```curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok```


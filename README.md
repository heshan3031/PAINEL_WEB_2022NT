![Login Admin Black](https://user-images.githubusercontent.com/105602625/177224804-97cdcf74-7899-4470-95ca-cae4cb43c7f5.jpg)
![Login Revenda Black](https://user-images.githubusercontent.com/105602625/177224808-97563e15-9031-4373-9416-1372d8efbf7f.jpg)

#SISTEMAS RECOMENDADO
Debian 8 
Ubuntu 14

# ATUALIZAR PACOTES DO SISTEMA
```
apt-get update -y; apt-get upgrade -y;
```

# INSTALAR PAINEL WEB 2022NT
```
wget raw.githubusercontent.com/wellzin-blip/v2022/master/gestorssh/install ; bash install
```

# DEFINIR/ALTERAR SENHA ROOT
```
wget raw.githubusercontent.com/wellzin-blip/v2022/master/gestorssh/senharoot ; bash senharoot
```

# SINCRONIZAR, CASO NÃO SEJA SSHPLUS PRO!
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/wellzin-blip/v2022/master/gestorssh/sincpainel && chmod +x sincpainel && dos2unix sincpainel && ./sincpainel
```

# SINCRONIZAR, CASO SEJA SSHPLUS PRO!
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/wellzin-blip/v2022/master/gestorssh/sincrazy && chmod +x sincrazy && dos2unix sincrazy && ./sincrazy
```

## :octocat: Credits
1. @crazy_vpn - Developer of SSHPlus Manager
2. @swittecnologia - Contributor 
```
☆ https://t.me/swittecnologia ☆
```
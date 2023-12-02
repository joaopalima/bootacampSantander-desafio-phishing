# Criando phishing para capturar senha do Facebook

Phishing para capturar *login* e *senha* de acesso do __Facebook__

## Utilizamos as seguintes ferramentas

-   Kali Linux
-   setoolkit

___

### Passos para criação do ataque de Phishing no Kali Linux para capturar senha do Facebook


1.   Acessar Terminal com usuário root:  `sudo su`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/7047db64-3607-4c23-b7d9-167f6ff63a2f)
2.   Iniciando o setoolkit:  `setoolkit`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/6b029d6c-a6ba-484d-b874-ec1381f658f1)
3.   Escolher o tipo de ataque:  `1) Social-Engineering Attacks`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/2e660a17-4778-4426-85d7-bf14c0bf7290)
4.   Vetor de ataque:  `2) Web Site Attack Vectors`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/067a8662-9f5b-4620-8781-a3cc1d43085c)

5.   Método escolhido de ataque:  `3) Credential Harvester Attack Method`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/2b55b340-7a58-4488-b3d3-9fd205b449cc)

6.   Método escolhido de ataque:  `2) Site Cloner`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/c91e3cda-7090-4883-a19c-50e04bf87d69)

7.   Endereço da máquina:  `ifconfig`
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/7be8d7c3-7805-4142-a301-4959f1ef6ce7)

8.   URL para clonar Facebook:  [http://www.facebook.com](http://www.facebook.com/)
-   ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/a96b4201-d790-4fe5-b76b-3c804ff853fa)

___


### **Resutado obtido no Ataque**

Utilizando uma VM com WindowsXP acessando o IP address [192.168.1.7], obtivemos o seguinte resultado:


![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/4d42f9a4-8277-419a-8a5f-5c28d5cbef2f)

![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/6288602e-b864-4e4c-93ab-f9b65c3bc228)

__**Log recebido com dados de acesso do usuário**__
-  ![image](https://github.com/joaopalima/bootacampSantander-desafio-phishing/assets/31939741/375735dd-4274-43bc-84b9-e27f4f1726f6)





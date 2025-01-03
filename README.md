# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resultados
![image](https://github.com/user-attachments/assets/175c92aa-6c0d-4693-b57b-44dcf8752da4)

> A proteção do Facebook geralmente impede a coleta usando o método "Website Cloner". Para contornar isso, é necessário clonar a página e utilizar a opção **Custom Import** do setoolkit.
![image](https://github.com/user-attachments/assets/b36e27bb-584b-4cad-9c0b-3f6cb0b9b621)

### Clonar a página do facebook (https://www.facebook.com/) para um arquivo index.html:
![image](https://github.com/user-attachments/assets/30139399-1e31-4408-8d17-749a900c9009)

### Selecionar a opção "Custom Import":
![image](https://github.com/user-attachments/assets/885c833d-9ca1-4ce5-9faf-9918f99bd1b3)

### Informar o caminho do diretório onde o arquivo index.html está criado:
![image](https://github.com/user-attachments/assets/b0c4e77c-ddb1-40f9-aee4-0a408dbc64fa)

### Informar a URL que será utilizada:
![image](https://github.com/user-attachments/assets/9692c102-ef81-4a01-a3ed-c16980f66e2f)


### Dessa maneira, o seltookit consegue capturar as informações, furando a proteção do facebook
![image](https://github.com/user-attachments/assets/8bc83465-ef27-4757-a166-0a6363cc65a1)





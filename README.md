# oministack-frontend-mobile
Frontend da aplicação Be The Hero desenvolvido em React Native, utilizando o [Expo](https://expo.io/).
Para rodar a aplicação, é preciso instalar as dependências ```npm install``` e iniciar com ```npm start```. 
Para rodar o aplicativo no celular, precisa baixar o app do Expo na loja do seu celular e ler o QR Code da aplicação que está rodando.
Localmente precisa modificar a variável baseURL em /src/services/api.js e apontar para o ip da máquina
Exemplo: [Imagem](https://imgur.com/a/jVEmmxo "imagem exemplo")
Com o exemplo da imagem, a variável baseURL deve apontar para: ```http://192.168.0.194:3001`` (Se o backend estiver rodando na porta 3001)

Utilizei as seguintes dependências:
- ```expo-mail-composer``` para envio de email

- ```intl``` para formatar valores para padrão de real 

- ```axios``` para requisições http

- ```expo-constants``` para pegar alguns dados como por exemplo tamanho da tela

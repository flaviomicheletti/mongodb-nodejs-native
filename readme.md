# Node Mongodb Native

Seguindo a documentação

http://mongodb.github.io/node-mongodb-native/3.5/quick-start/quick-start/


### Passo a passo

Precisa ter o Mongodb instalado

https://gist.github.com/flaviomicheletti/5a7e5cfc6555ef79ad3ec3d48d318b14


Instalando

    npm i

Executando

    node example01.js

    (node:23692) DeprecationWarning: current Server Discovery and Monitoring engine is deprecated, 
    and will be removed in a future version. To use the new Server Discover and Monitoring engine, 
    pass option { useUnifiedTopology: true } to the MongoClient constructor.
    Connected successfully to server

Após acrescentar `{ useNewUrlParser: true, useUnifiedTopology: true }`

Recebemos apenas...

    Connected successfully to server

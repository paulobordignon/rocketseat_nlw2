# rocketseat_nlw2 (Proffy)

<p style="text-align:center">
<img src="https://github.com/paulobordignon/rocketseat_nlw2/blob/master/web/src/assets/images/landing.svg"> 
</p>

### Execução
Instalar Node.js, Yarn e Expo. Posteriormente em cada pasta do projeto, deverá ser instalado as seguintes dependências:

#### cd web

```
yarn install
yarn add @types/react-router-dom -D
yarn add axios
yarn knex:migrate
```

#### cd server

```
yarn install
yarn add @types/cors -D
yarn add @types/express -D
yarn add ts-node-dev -D
yarn add knex
```

#### cd mobile

```
yarn install
expo install expo-font @expo-google-fonts/archivo @expo-google-fonts/poppins
yarn add @react-navigation/native
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
yarn add @react-navigation/stack
yarn add @react-navigation/bottom-tabs
yarn add axios
expo install @react-native-community/async-storage
```

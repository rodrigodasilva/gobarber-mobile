<h1 align="center">

<img src="src/assets/logo-purple.svg" width="180"/>
<br />
<br />
Meetapp Mobile

</h1>

<p align="center">
  <a href="#tecnologias-utilizadas">Tecnologias utilizadas</a> |
  <a href="#como-usar">Como Usar</a> |
  <a href="#funcionalidades">Funcionalidades</a>
</p>

<div align="center">

<img src="src/assets/example.gif" height="550"/>

</div>

Esta é o frontend Mobile de um projeto criado durante os módulos 8, 9 e 10 no Bootcamp da Rocketseat. Nele desenvolvemos um serviço apelidado de GoBarber onde os usuários podem se cadastrar como prestador de serviços através da [aplicação web](https://github.com/rodrigodasilva/gobarber-front-web) feita em ReactJS, e outros usuários podem agendar horários com estes prestadores através deste aplicativo, desenvolvido em React-native, sendo toda a lógica gerenciada pela [api](https://github.com/rodrigodasilva/backend-gobarber) desenvolvida em NodeJS.

## Tecnologias utilizadas

- [axios](https://github.com/axios/axios)
- [date-fns](https://github.com/date-fns/date-fns)
- [immer](https://github.com/immerjs/immer)
- [prop-types](https://github.com/facebook/prop-types)
- [react](https://github.com/facebook/react)
- [react-native](https://github.com/facebook/react-native)
- [react-native-gesture-handler](https://github.com/kmagiera/react-native-gesture-handler)
- [react-native-linear-gradient](https://github.com/react-native-community/react-native-linear-gradient)
- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)
- [react-navigation](https://github.com/react-navigation/react-navigation)
- [react-redux](https://github.com/reduxjs/react-redux)
- [reactotron-react-native](https://github.com/infinitered/reactotron-react-native)
- [reactotron-redux](https://github.com/infinitered/reactotron-redux)
- [reactotron-redux-saga](https://github.com/infinitered/reactotron-redux-saga)
- [redux](https://github.com/reduxjs/redux)
- [redux-persist](https://github.com/rt2zz/redux-persist)
- [redux-saga](https://github.com/redux-saga/redux-saga)
- [styled-components](https://github.com/styled-components/styled-components)

## Como usar

Pré-requisitos:

- Yarn/Npm
- [Back-end](https://github.com/rodrigodasilva/backend-gobarber) da aplicação rodando

Tendo isso, startamos o aplicativo

> react-native start

E carregamos no emulador do android

> react-native run-android

Ou, no emulador do iphone

> react-native run-ios

## Funcionalidades

- Autenticação
- Visualização dos agendamentos
- Realizar agendamento
- Cancelar agendamento
- Editar dados do perfil

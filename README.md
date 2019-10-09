### A aplicação

Esta api compõe um projeto desenvolvido durante a semana oministack, realizado pela RocketSeat. Nela, desenvolvemos uma aplicação base para compartilhamento de escritórios.
O projeto se compões de :
- Backend contruido com NodeJS,MongoDB e express.js;
- WebApp de administração contruido em ReactJS;
- Mobile contruido com React-Native e Socket.Io;

# Construção da WebApp

[![AirCnc_logo](https://i.imgur.com/vqdhqGZ.png "AirCnc_logo")](# "AirCnc_logo")

A empresa que cadastra seus escritórios, poderá receber as solicitações de reserva e aceitar ou não pela webapp. Recebendo e enviando informações em tempo real para o mobile via Socket.Io

Como funciona
=============

A empresa entra com seu e-mail, logo será levado a Dashboard, onde poderá cadastras seus escritórios, enviando foto, preço, tecnologias e nome. Após a criação, ela já está disponível para reserva no mobile.

Após um usuário solicitar a reserva pelo mobile, a webapp recebe em tempo real a solicição com nome do escritório e data. A partir disso, pela webapp, poderá rejeitar ou aceitar a solicitação, enviando de volta a informação ao mobile.

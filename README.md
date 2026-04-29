# 🌦️ CLIMA PRO 1.0

Esse foi meu primeiro projeto de previsão do tempo funcionando de verdade na web.
A ideia aqui foi sair da teoria e construir algo simples, mas que consome uma API real e entrega informação útil.

---

## 🔗 ACESSE O PROJETO

👉 https://etoffanin.github.io/Clima-Pro-1.0/

---

## 📸 PREVIEW

Versão no DeskTop
<img width="1023" height="535" alt="CLIMAPRO_" src="https://github.com/user-attachments/assets/15bca8c1-70d8-4c5f-820b-e0d5c876fc77" />

Versão no Celular
<img width="720" height="1600" alt="climapromob" src="https://github.com/user-attachments/assets/5d6f08a1-0e85-4acf-b11c-29522848c95d" />

*

---

## ✨ FUNCIONALIDADES

✔️ Busca de clima por cidade

✔️ Temperatura atual em tempo real

✔️ Condição do clima (ex: nublado, ensolarado)

✔️ Integração com API externa

✔️ Projeto online via GitHub Pages

✔️ Geolocalização automática


---

## 🧠 COMO FUNCIONA POR TRÁS

A lógica do projeto é:

1. O usuário digita o nome da cidade
2. O JavaScript captura esse valor
3. Faço uma requisição para a API usando `fetch`
4. Recebo os dados em JSON
5. Atualizo o HTML com as informações

Exemplo da requisição:

```javascript
fetch(`https://api.openweathermap.org/data/2.5/weather?q=${cidade}&appid=SUA_API_KEY&units=metric`)
```

Depois disso, uso os dados retornados pra mostrar:

* temperatura
* clima
* informações principais

Tudo isso manipulando o DOM.

---

## 🛠️ TECNOLOGIAS UTILIZADAS

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* OpenWeather API
* Git & GitHub

---

## 📚 O QUE EU TREINEI AQUI

Esse projeto foi importante pra praticar:

* consumo de API na prática
* manipulação de dados JSON
* atualização dinâmica da interface
* estruturação de um projeto front-end
* versionamento com Git

---

## ⚙️ COMO RODAR LOCALMENTE

```bash
git clone https://github.com/etoffanin/Clima-Pro-1.0.git
cd Clima-Pro-1.0
```

Depois é só abrir o arquivo **index.html** no navegador.

---

## 🚀 PRÓXIMA EVOLUÇÃO (2.0)

Quero evoluir esse projeto com:

* 🌙 Tema dinâmico (dia/noite)
* 📅 Previsão para vários dias
* 🎨 Interface mais moderna
* 📱 Melhor experiência no celular

---

## 👨‍💻 SOBRE MIM

Meu nome é Enzo e estou começando na área de desenvolvimento.
Esse projeto faz parte da minha evolução prática.

---

Desenvolvido por Enzo Toffanin


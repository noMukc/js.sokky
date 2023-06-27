# 👣 Sokky.js

💛Sokky.js - это легковесная библиотека для Node.js, которая позволяет создавать мощные Discord боты, которые могут быть интегрированы в любой Discord сервер.

[![npm version](https://badge.fury.io/js/sokky.svg)](https://badge.fury.io/js/sokky)
[![Downloads](https://img.shields.io/npm/dm/sokky.svg)](https://www.npmjs.com/package/sokky)
![License](https://img.shields.io/npm/l/sokky.svg)

---

## 🏅 Особенности

- Легкий в использовании и интеграции в любую платформу обмена сообщениями
- Мощная обработка естественного языка для сложных взаимодействий
- Настраиваемый и расширяемый для удовлетворения вашего дизайна
- Легковесный и быстрый в работе

---

## 👉 Установка
> - **NodeJs Version : LTS  ( v18 )**

```bash
### npm
npm install sokky.js

### yarn (soon)
yarn add sokky.js
```

## 🌟 Использование

```js
const sokky = require('sokky.js');

// Создать новый экземпляр бота
const bot = sokky.createBot({
  token: 'YOUR_DISCORD_BOT_TOKEN',
  prefix: '!'
});

// Добавить команды в бота
bot.command('ping', (msg, args) => {
  msg.channel.send('Pong!');
});

// Запустить бота
bot.login();
```

## Присоединиться к нашему Discord сообществу!

> *Присоединяйтесь к нашему Discord серверу, где вы можете найти людей с общими интересами, подключиться к сообществу и получить помощь и поддержку по нашему проекту.*

[Нажмите, чтобы присоединиться!](https://discord.gg/NJNbC7rc)

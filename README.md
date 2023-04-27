# Экспериментальный телеграм чатбот с использованием api openai.

## Как использовать?

1. Клонировать проект 
2. установить зависимости npm i
3. В файле default.json ввести свои ключи от своего телеграм бота и openai (https://platform.openai.com/account/api-keys)
4. Далее запускаем npm run dev
5. Заходим в телеграм и запускаем свой бот. 

## Можно задавать вопросы текстом или голосом

## Docker

   build:
	    docker build -t tgbot .

   run:
	    docker run -d -p 3000:3000 --name tgbot --rm tgbot

goit-nodejs-hw-01

Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
image.png
Получаем контакт по id
node index.js --action get --id 5
image.png
Добавялем контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
image.png
Удаляем контакт
node index.js --action remove --id=3
image.png
# ✅ React Todo App with API — Complete

## 🔗 Live Preview

[DEMO](https://kostivkostiv.github.io/Todo_App/)

## 🛠 Technologies Used

- ⚛️ React  
- 🎨 SCSS  
- 🧠 JavaScript (ES6+)  
- 🔄 REST API  
- 🚀 Vite  
- 🌍 GitHub Pages

## 🚀 Getting Started

- `git clone https://github.com/kostivkostiv/react-todo-app.git`
- `cd react-todo-app`
- `npm install`
- `npm start`

## ⚙️ Functionality

### 🔄 Toggle статусу completed

- Натискання чекбокса змінює статус completed тудушки.
- Під час очікування відповіді API — тудушка перекривається лоадером.
- Зміна статусу відбувається лише після успішної відповіді.
- У випадку помилки — показується повідомлення Unable to update a todo.

### ✅ Toggle All

- toggleAll активується, лише якщо всі тудушки виконані.
- При натисканні — встановлюється протилежний статус для всіх тудушок.
- Запит надсилається тільки для тудушок, статус яких справді змінюється.
- Масове оновлення — імітує кілька окремих API-викликів.

### ✏️ Редагування тудушки

- Подвійний клік по заголовку → активує режим редагування.
- Замість заголовка і кнопки x зʼявляється форма з інпутом.

Якщо новий текст:

🔁 такий самий як старий → нічого не робиться

 🧹 пустий → тудушка видаляється

✏️ змінений → показується лоадер, зберігається після відповіді API

У разі помилки — показується відповідне повідомлення (Unable to update або Unable to delete)


# 💻 Приклади з теми "HTML: структура веб-сторінок"

## 1. Базова структура HTML-документа
```html
<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>Моя перша сторінка</title>
</head>
<body>
  <h1>Привіт, світ!</h1>
  <p>Це моя перша веб-сторінка.</p>
</body>
</html>

<header>
  <h1>Новини школи</h1>
</header>
<nav>
  <ul>
    <li><a href="index.html">Головна</a></li>
    <li><a href="news.html">Новини</a></li>
    <li><a href="contacts.html">Контакти</a></li>
  </ul>
</nav>
<main>
  <article>
    <h2>Перемога у конкурсі</h2>
    <p>Наша команда здобула перше місце у міському конкурсі.</p>
  </article>
</main>
<footer>
  <p>© 2026 Шкільний сайт</p>
</footer>

<table border="1">
  <caption>Розклад уроків</caption>
  <tr>
    <th>День</th>
    <th>Предмет</th>
    <th>Кабінет</th>
  </tr>
  <tr>
    <td>Понеділок</td>
    <td>Математика</td>
    <td>101</td>
  </tr>
  <tr>
    <td>Вівторок</td>
    <td>Інформатика</td>
    <td>202</td>
  </tr>
</table>

<form action="submit.php" method="post">
  <label for="name">Ім’я:</label>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required><br><br>

  <label for="message">Повідомлення:</label><br>
  <textarea id="message" name="message" rows="5"></textarea><br><br>

  <button type="submit">Надіслати</button>
</form>

<video width="400" controls>
  <source src="school-video.mp4" type="video/mp4">
  Ваш браузер не підтримує відео.
</video>

<p>Відвідайте наш <a href="https://school.edu">шкільний сайт</a>.</p>
<img src="images/school.jpg" alt="Фото школи" width="300">

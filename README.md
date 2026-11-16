# Інвестувати чи витрачати? — калькулятор Чорної п’ятниці ICU

Статичний сайт: `index.html` + шрифти e-Ukraine у `fonts/`. Збірка не потрібна.

## Публікація на GitHub Pages
1. Створіть репозиторій на GitHub (наприклад, `black-friday-calc`).
2. Завантажте в корінь репозиторію весь вміст цієї папки: `index.html`, `fonts/`, `.nojekyll`, `README.md`.
3. Settings → Pages → Source: «Deploy from a branch», Branch: `main`, папка `/ (root)` → Save.
4. Через хвилину-дві сайт буде на `https://<ваш-логін>.github.io/<назва-репозиторію>/`.

## Свій домен (за потреби)
Settings → Pages → Custom domain → введіть домен і додайте CNAME-запис у DNS. Увімкніть «Enforce HTTPS» —
меню «Поділитися» на телефонах працює лише через HTTPS.

## Адреса
Сайт: https://publicicu.github.io/black-friday-calc/

Якщо підключите свій домен, замініть цю адресу в `<link rel="canonical">` і `og:url` у `index.html` — з неї кнопки Facebook/Threads і «Скопіювати текст» беруть посилання.

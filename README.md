# 🌿 SOKOLOVA — Massage Studio

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Online-success?style=for-the-badge&logo=githubpages&logoColor=white)](https://gennadijvaliev02-design.github.io/Sokolova/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-blueviolet?style=for-the-badge)](https://gennadijvaliev02-design.github.io/Sokolova/)

> Официальный сайт и сервис онлайн-записи студии массажа и коррекции фигуры **SOKOLOVA** (Москва, м. Октябрьское поле).  
> Разработан в концепции премиального велнеса: глубокие изумрудные тона (`#153b31`), акценты теплого золота (`#aa9364`), интерактивные сравнения результатов «До / После» и пошаговое бронирование в WhatsApp.

🔗 **Рабочий сайт**: [https://gennadijvaliev02-design.github.io/Sokolova/](https://gennadijvaliev02-design.github.io/Sokolova/)

---

## ✨ Ключевые возможности проекта

- **Интерактивные сравнения «До / После»**:
  - Кастомный двухслойный слайдер сравнения результатов процедур с плавным перемещением разделителя (сенсорный ввод и мышь).
  - Сетка реальных кейсов студии по коррекции фигуры и антицеллюлитным программам.
- **Интерактивный 4-шаговый модуль записи**:
  - **Шаг 1**: Выбор услуги и длительности (пробные сеансы, массаж тела, лица, обёртывания).
  - **Шаг 2**: Выбор конкретного мастера студии с учётом его специализации.
  - **Шаг 3**: Выбор свободной даты.
  - **Шаг 4**: Выбор удобного времени.
  - **Интеграция с WhatsApp**: после выбора всех параметров генерируется готовое структурированное сообщение для быстрой записи у администратора студии.
- **Структурированный каталог услуг и прайс-лист**:
  - Удобная навигация по вкладкам: *Женский прайс, Лицо и спина, Мужской массаж*.
  - Прозрачная система абонементов (1, 5, 7 и 10 сеансов со скидками и сроками действия).
  - Специальный блок пробных сеансов для новых клиентов.
- **Команда мастеров**:
  - Карточки специалистов с указанием опыта, образования и ключевых методик (классический, лимфодренажный, спортивный, реабилитация).
- **Плавные микроанимации и эстетика**:
  - Интерактивная floating-скульптура с мягким параллакс-откликом.
  - Линейная векторная графика с плавной отрисовкой при скролле.
  - Адаптивная мобильная кнопка быстрой записи (`floating CTA`).

---

## 📂 Структура файлов

```text
Sokolova/
├── assets/
│   ├── floating/                   # Ассеты декоративной 3D-скульптуры
│   ├── favicon.svg                 # Векторный фавикон студии
│   ├── og-sokolova.jpg             # Превью для соцсетей (1200x630)
│   └── *.jpeg, *.jpg, *.png        # Фотографии интерьера, мастеров и кейсов
├── index.html                      # Семантическая разметка и логика сайта
└── README.md                       # Документация проекта
```

---

## 🚀 Локальный запуск

```bash
# Клонирование репозитория
git clone https://github.com/gennadijvaliev02-design/Sokolova.git

# Переход в папку
cd Sokolova

# Запуск локального сервера
python3 -m http.server 8080
# или
npx serve .
```

Открыть в браузере: `http://localhost:8080`.

---

## 🛠 Технологии

- **HTML5**: семантическая разметка, доступность, Open Graph теги.
- **CSS3**: Custom Properties (Variables), Flexbox, CSS Grid, Clamp typography, Media Queries.
- **Vanilla JavaScript**: управление модальным окном, пошаговый мастер бронирования, синхронизация скроллеров и слайдеров «До / После».
- **Hosting**: GitHub Pages.

---

## 📬 Автор

- **GitHub**: [@gennadijvaliev02-design](https://github.com/gennadijvaliev02-design)

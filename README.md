# 🌴 Phu Quoc Guide — Payload CMS Travel Portal

Информационный портал по острову Фукуок для туристов: визы, пляжи, транспорт, районы, рестораны, маршруты и практические советы.

Проект построен на:

* Payload CMS
* Next.js App Router
* TypeScript
* PostgreSQL
* SSR + SEO
* Layout Builder
* Search
* Dynamic Pages

---

# 🚀 Что уже реализовано

## Контентная система

### Posts

Статьи и гайды:

* визы
* транспорт
* пляжи
* рестораны
* цены
* маршруты
* интернет
* аренда байков
* советы туристам

---

### Categories

SEO-структура портала:

* Перед поездкой
* На острове
* План поездки
* Советы и лайфхаки
* Пляжи
* Транспорт
* Где поесть
* Срочная помощь

---

### Pages

CMS-страницы:

* Главная
* О проекте
* Контакты
* FAQ
* Политика

---

### Media

Медиа библиотека:

* фото пляжей
* карты
* рестораны
* транспорт
* баннеры
* hero изображения

---

# 🧱 Структура сайта

## Главная

* Hero секция
* Поиск
* Быстрые действия
* Популярные статьи
* Подборки
* Срочная помощь
* План поездки
* Уже на острове

---

## Перед поездкой

* Виза
* Когда ехать
* Бюджет
* Перелёт
* Что взять
* Районы

---

## На острове

* Где поесть
* Пляжи
* Что посмотреть
* Транспорт
* Интернет
* Аптеки
* Обмен валют

---

## План поездки

* 3 дня
* 5 дней
* 7 дней
* Для семьи
* Бюджетный отдых
* Премиум отдых

---

# 🔍 SEO структура

## Раздел → Кластер → Статья

Пример:

```txt
/pered-poezdkoy/viza/viza-vetnam-2026
```

```txt
/na-ostrove/plyazhi/luchshie-plyazhi-fukuoka
```

---

# 🎨 UI / Design

Интерфейс выполнен в стиле современного travel media портала:

* светлый бежевый фон
* тёмно-бирюзовые акценты
* большие serif заголовки
* мягкие карточки
* mobile-first layout
* sticky header
* responsive grid

---

# ⚡ Основные возможности

* Dynamic routes
* SSR rendering
* Payload blocks
* Rich text editor
* SEO metadata
* Search
* Categories
* Related posts
* Draft / Publish workflow
* Admin panel

---

# 📁 Основные коллекции

```txt
collections/
├── Posts
├── Categories
├── Pages
├── Media
├── Users
```

---

# 📁 Frontend структура

```txt
src/app/(frontend)
├── page.tsx
├── [slug]/page.tsx
├── post/[slug]/page.tsx
├── search/page.tsx
```

---

# 📱 Mobile UX

Оптимизация под туристов:

* быстрые кнопки
* короткие блоки
* поиск сверху
* крупные CTA
* быстрый доступ к важному

---

# 🔥 MVP

Первая версия включает:

* Главную страницу
* Категории
* Посты
* SEO структуру
* Поиск
* 50+ статей
* Responsive UI

---

# 🛣 Roadmap

## Далее:

* Каталог мест
* Карта острова
* Фильтры
* Маршруты
* Личный кабинет
* Избранное
* AI поиск
* Telegram интеграция

---

# ⚙️ Запуск проекта

```bash
pnpm install
pnpm dev
```

---

# 🌐 Админка

```txt
http://localhost:3000/admin
```

---

# 🧩 Технологии

* Payload CMS
* Next.js
* TypeScript
* PostgreSQL
* Tailwind / CSS
* Lexical Editor

---


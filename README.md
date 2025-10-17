# 📱 FakeFeed

> **Современная социальная сеть с минималистичным дизайном и плавными анимациями**

![FakeFeed Preview](https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-Strict-blue?style=for-the-badge&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-Fast-purple?style=for-the-badge&logo=vite)
![SCSS](https://img.shields.io/badge/SCSS-Modules-pink?style=for-the-badge&logo=sass)

## ✨ Особенности

- 🎨 **Минималистичный дизайн** с градиентным фоном и glassmorphism эффектами
- ⏰ **Реальное время** с аналоговыми часами
- 📅 **Поиск по дате** с точным отображением постов
- ♾️ **Бесконечная прокрутка** с плавными анимациями
- 📱 **Адаптивный дизайн** для всех устройств
- 🎭 **Анимированные посты** с эмодзи и градиентами
- 🔍 **Умный поиск** с загрузкой контекстных постов

## 🚀 Быстрый старт

```bash
# Установка зависимостей
npm install

# Запуск в режиме разработки
npm run dev

# Сборка для продакшена
npm run build

# Сборка для Netlify (с проверками)
npm run build:netlify

# Предварительный просмотр сборки
npm run preview
```

## 🌐 Деплой на Netlify

### Автоматический деплой

1. Подключите репозиторий к [Netlify](https://netlify.com)
2. Настройки сборки:
   - **Build command:** `npm run build:netlify`
   - **Publish directory:** `dist`
   - **Node version:** `18`

### Ручной деплой

```bash
# Установка Netlify CLI
npm install -g netlify-cli

# Деплой
netlify deploy --prod
```

📖 **Подробная инструкция:** [NETLIFY_DEPLOY.md](./NETLIFY_DEPLOY.md)

## 🛠️ Технологии

- **Frontend**: React 19, TypeScript (Strict Mode)
- **Стилизация**: SCSS Modules, CSS-in-JS
- **Сборка**: Vite
- **Тестирование**: Cypress E2E
- **Состояние**: React Query, Custom Hooks
- **Анимации**: CSS Keyframes, Intersection Observer

## 📁 Структура проекта

```
src/
├── components/          # React компоненты
│   ├── ui/             # Переиспользуемые UI элементы
│   ├── Post/           # Компонент поста
│   ├── NewsFeed/       # Лента новостей
│   └── DateSearch/     # Поиск по дате
├── hooks/              # Кастомные хуки
├── services/           # API и моковые данные
├── styles/             # Глобальные стили
└── types/              # TypeScript типы
```

## 🎯 Основные компоненты

### 📱 NewsFeed

- Бесконечная прокрутка с React Query
- Анимации появления постов
- Поиск по дате с контекстной загрузкой

### ⏰ RealtimeClock

- Аналоговые часы с плавной анимацией стрелок
- Синхронизация с системным временем
- Минималистичный дизайн

### 🔍 DateSearch

- Календарь с выбором даты
- Кнопка "Today" для быстрого перехода
- Glassmorphism эффекты

## 🎨 Дизайн-система

- **Цвета**: Темная тема с градиентными акцентами
- **Типографика**: SF Pro Display, системные шрифты
- **Анимации**: Cubic-bezier переходы, плавные трансформации
- **Эффекты**: Backdrop-filter, box-shadow, градиенты

## 🧪 Тестирование

```bash
# Запуск E2E тестов
npm run cypress:open

# Запуск тестов в headless режиме
npm run cypress:run
```

## 📝 Скрипты

- `npm run dev` - Запуск dev сервера
- `npm run build` - Сборка проекта
- `npm run preview` - Предварительный просмотр
- `npm run lint` - Проверка кода ESLint
- `npm run type-check` - Проверка типов TypeScript

## 🎭 Особенности UX

- **Плавные анимации** при скролле и взаимодействии
- **Интуитивная навигация** по датам
- **Визуальная обратная связь** для всех действий
- **Оптимизированная производительность** с lazy loading

## 📄 Лицензия

MIT License - свободно используйте и модифицируйте

---

<div align="center">

**Создано с ❤️ для демонстрации современных веб-технологий**

[🌐 Демо](https://your-demo-url.com) • [📧 Контакты](mailto:your-email@example.com)

</div>

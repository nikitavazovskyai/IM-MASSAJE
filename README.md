<div align="center">
<img width="1200" height="475" alt="IASTM Massage Course" src="https://images.unsplash.com/photo-1600334089648-b0d9d3028eb2?q=80&w=1200&h=475&auto=format&fit=crop" />
</div>

# Онлайн-курс инструментального массажа (IASTM)

Профессиональный сайт-воронка для продажи онлайн-курса по инструментальному массажу мягких тканей.

## Особенности

✨ **Интерактивный дизайн**
- Современный Dark Mode интерфейс
- Smooth-скролл и анимации
- Адаптивный дизайн (мобильный, планшет, ПК)

🎓 **Образовательный контент**
- 5 модулей обучения
- 20+ видеоуроков
- Интерактивные тесты
- Пошаговые протоколы

💰 **Инструменты продаж**
- ROI калькулятор окупаемости
- Форма регистрации на курс
- Демо-версия уроков
- Администраторская панель лидов

📱 **Функциональность**
- LocalStorage для сохранения лидов
- Симуляция платежной системы
- Именной сертификат (динамический)
- Уведомления активности на сайте

## Технологии

- **React 19** - UI фреймворк
- **TypeScript** - типизация
- **Tailwind CSS 4** - стили
- **Vite** - сборщик
- **Motion** - анимации
- **Lucide React** - иконки

## Быстрый старт

### Установка зависимостей
```bash
npm install
```

### Локальная разработка
```bash
npm run dev
```
Сайт будет доступен на `http://localhost:3000`

### Сборка для продакшена
```bash
npm run build
```

### Проверка типов
```bash
npm run lint
```

## Структура проекта

```
src/
├── components/           # React компоненты
│   ├── Header.tsx       # Навигация
│   ├── Hero.tsx         # Главный экран
│   ├── MainResults.tsx  # Результаты обучения
│   ├── TrialLessons.tsx # Пробные уроки
│   ├── Syllabus.tsx     # Программа курса
│   ├── RoiCalculator.tsx # Калькулятор ROI
│   ├── CourseIncludes.tsx # Что входит
│   ├── Certificate.tsx  # Сертификат
│   ├── Testimonials.tsx # Отзывы
│   ├── LeadForm.tsx     # Форма регистрации
│   ├── LeadDashboard.tsx # Панель лидов
│   └── NotificationToast.tsx # Уведомления
├── App.tsx              # Главное приложение
├── main.tsx             # Точка входа
├── index.css            # Глобальные стили
└── types.ts             # TypeScript типы
```

## Компоненты

### Header
Фиксированная навигация с логотипом и CTA кнопками.

### Hero
Главный экран с предложением и видеодемо.

### MainResults
3 основных результата обучения в виде карточек.

### TrialLessons
Интерактивные пробные уроки с видео-плеером и тестами.

### Syllabus
Аккордеон с полной программой курса.

### RoiCalculator
Интерактивный калькулятор ROI с слайдерами.

### CourseIncludes
Bento-grid с преимуществами курса.

### Certificate
Динамический сертификат с предпросмотром.

### Testimonials
Отзывы студентов с результатами.

### LeadForm
Модальное окно регистрации и симуляции платежа.

### LeadDashboard
Админская панель для управления лидами.

## Конфигурация

### Переменные окружения

Создайте `.env.local`:

```env
GEMINI_API_KEY=your_api_key_here
APP_URL=http://localhost:3000
```

## Развёртывание

### Vercel
```bash
npm install -g vercel
vercel
```

### GitHub Pages
```bash
npm run build
git add dist/
git commit -m "Deploy to GitHub Pages"
git push
```

## Лицензия

MIT

## Автор

Nikitavazovskyai - [GitHub](https://github.com/nikitavazovskyai)

---

**Создано с ❤️ для массажистов**

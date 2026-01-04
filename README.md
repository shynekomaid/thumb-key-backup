# Thumb-key Hyper Layers

> Custom **thumb-key** configuration for advanced text navigation, editing, and typography.

This repository contains two files:

* `thumb.yml` — the actual thumb-key layout configuration
* `*.zip` — a full application backup (including databases)

Both files are meant to be **imported via the thumb-key application UI**, not edited manually inside the app.

---

## 📁 Files

### `thumb.yml`

The main configuration file.

Includes:

* **ENHyper** — English-focused hyper layer
* **RUHyper** — Cyrillic layer with Ukrainian extensions

Features:

* Word-wise cursor navigation
* Word-wise deletion
* Combining diacritics (◌́)
* Typography helpers (— « »)
* Non-breaking space
* Currency symbols (₴ ₽)

This file is safe to version, edit, and tweak.

---

### `*.zip`

Full application backup created by thumb-key.

Includes:

* All layouts
* Databases
* App state and internal metadata

⚠️ **Important**:

* This file is **not human-readable**
* Do not try to edit it manually
* Intended only for full restore or migration

---

## 📥 Import Instructions (EN)

### Import `thumb.yml`

1. Open the **thumb-key** application
2. Go to **Settings → Import / Export**
3. Choose **Import layout / config**
4. Select `thumb.yml`
5. Apply and restart the app if needed

### Import full backup

1. Open the **thumb-key** application
2. Go to **Settings → Import / Export**
3. Choose **Restore from backup**
4. Select the `*.zip` file
5. Confirm restore (this will overwrite current data)

---

## ⚠️ Notes

* Importing a backup will **replace existing layouts and data**
* If you only want the hyper layers, import **`thumb.yml` only**
* Backup import is recommended for:

  * New device setup
  * Full environment migration

---

## 🧠 Design Philosophy

* **Main layer** — navigation (safe actions)
* **Shifted layer** — destructive actions (delete by word)
* **Numeric layer** — typography & special symbols

The layout is optimized for:

* Text-heavy work
* Editing and proofreading
* Minimal finger travel
* Strong muscle memory

---

---

# Thumb-key Hyper Layers (Українською)

> Кастомна **thumb-key** конфігурація для навігації по тексту, редагування та типографії.

У репозиторії є два файли:

* `thumb.yml` — основний файл конфігурації
* `*.zip` — повний бекап застосунку (разом із базами даних)

Обидва файли **імпортуються через інтерфейс програми thumb-key**.

---

## 📁 Файли

### `thumb.yml`

Основний файл розкладки.

Містить:

* **ENHyper** — гіпер-шар для англійської
* **RUHyper** — кириличний шар з українськими літерами

Можливості:

* Навігація по словах
* Видалення по словах
* Комбінуючі діакритики (◌́)
* Типографія (— « »)
* Нерозривний пробіл
* Валютні символи (₴ ₽)

Файл безпечний для редагування та версіонування.

---

### `*.zip`

Повний бекап, створений програмою thumb-key.

Містить:

* Усі розкладки
* Бази даних
* Внутрішній стан програми

⚠️ **Важливо**:

* Файл **не призначений для ручного редагування**
* Використовується лише для повного відновлення

---

## 📥 Інструкція з імпорту (UA)

### Імпорт `thumb.yml`

1. Відкрийте програму **thumb-key**
2. Перейдіть у **Settings → Import / Export**
3. Оберіть **Import layout / config**
4. Виберіть файл `thumb.yml`
5. Застосуйте зміни (за потреби перезапустіть програму)

### Імпорт повного бекапу

1. Відкрийте **thumb-key**
2. Перейдіть у **Settings → Import / Export**
3. Оберіть **Restore from backup**
4. Виберіть файл `*.zip`
5. Підтвердіть відновлення (поточні дані буде перезаписано)

---

## ⚠️ Зауваження

* Відновлення з бекапу **замінює всі поточні дані**
* Якщо вам потрібні лише hyper-шари — імпортуйте **тільки `thumb.yml`**
* Повний бекап корисний для:

  * Налаштування нового пристрою
  * Міграції середовища

---

## 🧠 Філософія дизайну

* **Main** — навігація та безпечні дії
* **Shifted** — деструктивні операції
* **Numeric** — типографія та спецсимволи

Розкладка оптимізована для:

* Роботи з текстами
* Редагування та вичитки
* Мінімального руху пальців
* Стабільної мʼязової памʼяті

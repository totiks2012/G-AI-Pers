# G-AI-Pers eng version

A lightweight, web-based tool for creating, customizing, and saving AI prompts. Designed for developers, designers, and content creators to generate structured prompts for AI models like ChatGPT, Midjourney, or Claude. Available in two versions: English (`g-ai-per_4-en.html`) and Russian (`g-ai-per_4-ru.html`).

## Purpose

G-AI-Pers helps users craft detailed and customized prompts for AI systems. It provides a structured interface to define main prompts, settings, exceptions, actions, references, and styles, with 24 unique parameters (e.g., "Multilayered", "Dynamic") to fine-tune the tone and complexity of the prompt. Whether you're generating text, images, or code, this tool streamlines the process and saves your configurations for reuse.

## Features
- **Customizable Parameters**: Adjust 24 parameters (e.g., "Multilayered", "Allegorical") with 5 intensity levels (Minimal to Highest).
- **Dual Areas**: Work with two independent areas to organize different prompt sets.
- **Preset Management**: Save presets to browser storage (`localStorage`) or download as `.txt` files, and load them back easily.
- **Responsive Design**: Built with Tailwind CSS for a modern, mobile-friendly interface.
- **Help System**: Built-in help modal with detailed descriptions of each parameter.
- **Optimized Performance**: Uses debounced inputs and cached presets for a smooth experience.
- **Icon Support**: Integrates Font Awesome icons for intuitive navigation.
- **Multilingual**: English and Russian versions available.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/totiks2012/G-AI-Pers.git

Navigate to the project folder:
bash

cd G-AI-Pers

Open one of the following files in a web browser (no server required):
For English: g-ai-per_4-en.html

For Russian: g-ai-per_4-ru.html

Usage
Create a Prompt:
Go to the "Main Prompt" section and enter your primary AI prompt.

Use other sections ("Exceptions", "Actions", "References", "Style Prompt") to add specific instructions or constraints.

Customize Settings:
In the "Settings" section, adjust the 24 parameters (e.g., set "Dynamic" to "Above Average") to fine-tune the prompt's tone and style.

Save Presets:
Click "Save Preset" to store the configuration in browser storage.

Use "Save to Disk" to download the preset as a .txt file.

Load Presets:
Click "Load Preset" to upload a .txt file or select a saved preset from the "Presets" panel.

Explore Parameters:
Click "Help" to view detailed descriptions of each parameter to understand their impact.

Switch Areas:
Use "Area 1" and "Area 2" buttons to work on different prompt sets without overwriting.

Example
Main Prompt: "Generate a futuristic cityscape concept for a sci-fi novel."
Settings: Multilayered: Highest, Dynamic: Above Average, Minimalistic: Minimal.
Style Prompt: "Use vivid, cinematic descriptions with a cyberpunk aesthetic."
Saved as: futuristic-city.txt
Technologies
HTML5

CSS3 (Tailwind CSS)

JavaScript

Font Awesome (icons)

License
GNU General Public License v3.0 (LICENSE)
Contributing
Contributions are welcome! Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss your ideas.
Contact
GitHub: totiks2012
Demo
[Insert link to live demo, e.g., https://totiks2012.github.io/G-AI-Pers/g-ai-per_4-en.html]

---

### README.ru.md (на русском)

```
# G-AI-Pers

Лёгкое веб-приложение для создания, настройки и сохранения промптов для искусственного интеллекта. Разработано для программистов, дизайнеров и создателей контента, чтобы генерировать структурированные промпты для моделей ИИ, таких как ChatGPT, Midjourney или Claude. Доступно в двух версиях: английской (`g-ai-per_4-en.html`) и русской (`g-ai-per_4-ru.html`).

## Назначение

G-AI-Pers помогает создавать детализированные и кастомизированные промпты для ИИ-систем. Приложение предоставляет удобный интерфейс для задания основного промпта, настроек, исключений, действий, ссылок и стилей, с 24 уникальными параметрами (например, "Multilayered", "Dynamic") для настройки тона и сложности промпта. Независимо от того, создаёте ли вы текст, изображения или код, этот инструмент упрощает процесс и сохраняет ваши конфигурации для повторного использования.

## Возможности
- **Настраиваемые параметры**: 24 параметра (например, "Multilayered", "Allegorical") с 5 уровнями интенсивности (от "Minimal" до "Highest").
- **Две области**: Работайте с двумя независимыми областями для организации разных наборов промптов.
- **Управление пресетами**: Сохраняйте пресеты в браузере (`localStorage`) или скачивайте как `.txt` файлы, а также загружайте их обратно.
- **Адаптивный дизайн**: Построен на Tailwind CSS для современного и мобильного интерфейса.
- **Справка**: Встроенная справка с подробными описаниями каждого параметра.
- **Оптимизация**: Использует дебouncing для ввода и кэширование пресетов для плавной работы.
- **Иконки**: Интеграция с Font Awesome для интуитивной навигации.
- **Мультиязычность**: Доступны английская и русская версии.

## Установка

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/totiks2012/G-AI-Pers.git

Перейдите в папку проекта:
bash

cd G-AI-Pers

Откройте один из следующих файлов в веб-браузере (сервер не требуется):
Для английской версии: g-ai-per_4-en.html

Для русской версии: g-ai-per_4-ru.html

Использование
Создание промпта:
Перейдите в раздел "Main Prompt" (или "Основной промпт" в русской версии) и введите основной промпт для ИИ.

Используйте другие разделы ("Exceptions", "Actions", "References", "Style Prompt") для добавления конкретных инструкций или ограничений.

Настройка параметров:
В разделе "Settings" (или "Настройки") настройте 24 параметра (например, установите "Dynamic" на "Above Average") для управления тоном и стилем промпта.

Сохранение пресетов:
Нажмите "Save Preset" (или "Сохранить пресет") для сохранения конфигурации в браузере.

Используйте "Save to Disk" (или "Сохранить на диск") для скачивания пресета в виде .txt файла.

Загрузка пресетов:
Нажмите "Load Preset" (или "Загрузить пресет") для загрузки .txt файла или выберите сохранённый пресет в панели "Presets".

Изучение параметров:
Нажмите "Help" (или "Справка") для просмотра подробных описаний каждого параметра и их влияния.

Переключение областей:
Используйте кнопки "Area 1" и "Area 2" (или "Область 1" и "Область 2") для работы с разными наборами промптов без перезаписи.

Пример
Основной промпт: "Создать концепт футуристического города для научно-фантастического романа."
Настройки: Multilayered: Highest, Dynamic: Above Average, Minimalistic: Minimal.
Стиль: "Используйте яркие, кинематографические описания с эстетикой киберпанка."
Сохранено как: futuristic-city.txt
Технологии
HTML5

CSS3 (Tailwind CSS)

JavaScript

Font Awesome (иконки)

Лицензия
GNU General Public License v3.0 (LICENSE)
Как внести вклад
Приветствуются любые улучшения! Пожалуйста, создавайте issues или pull requests. Для крупных изменений сначала откройте issue для обсуждения.
Контакты
GitHub: totiks2012
Демо
[Вставьте ссылку на демо, например, https://totiks2012.github.io/G-AI-Pers/g-ai-per_4-en.html]


   

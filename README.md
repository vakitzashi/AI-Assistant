# Проект: "ИИ-ассистент для строительной компании"

Ссылка на проект в Telegram - @dreambrickbot

## Описание проекта
Проект направлен на создание интеллектуального ассистента, который будет автоматизировать взаимодействие с клиентами строительной компании. ИИ-ассистент способен осмысленно вести диалог, предоставлять информацию из базы знаний, помогать клиентам в выборе услуг и записывать их на звонок к менеджеру. Это позволит оптимизировать процесс обработки запросов, повысить конверсию и улучшить качество обслуживания.

![Иллюстрация к проекту](https://raw.githubusercontent.com/vakitzashi/AI-Assistant/refs/heads/main/bot1.png)
![Иллюстрация к проекту](https://github.com/vakitzashi/AI-Assistant/blob/main/bot2.png?raw=true)
*Скриншоты демонстрируют распознавание различных форм слова, сленга, числительных написанных текстом.
---

## Функционал

### 1. **Осмысленное ведение диалога**
   - Ассистент использует нейросетевые технологии для понимания контекста вопросов и предоставления релевантных ответов.
   - Способен поддерживать естественный диалог, адаптируясь к потребностям клиента.
   - В случае сложных запросов, которые требуют участия человека, ассистент перенаправляет клиента к менеджеру.

### 2. **Ответы на вопросы по базе знаний**
   - Интеграция с базой знаний компании, содержащей информацию о предоставляемых услугах, ценах, сроках выполнения работ и других деталях.
   - Ассистент быстро находит ответы на вопросы клиентов, исключая необходимость обращения к менеджеру для решения стандартных задач.
   - Ассистент защищён от спама - он ведет диалог только о сфере строительства и недвижимости и не позваоляет вести диалоговую ветку более 20 сообщений на 1 аккаунт.

### 3. **Ведение клиента по воронке продаж**
   - Ассистент помогает клиентам на каждом этапе воронки продаж:
     - Отвечает на вопросы о продуктах и услугах.
     - Предоставляет рекомендации на основе предпочтений клиента.
     - Мотивирует клиента к следующему шагу (например, запись на звонок).

### 4. **Запись на звонок менеджера**
   - Клиент может выбрать удобное время для звонка менеджера через интерфейс ассистента.
   - Выбранное время автоматически добавляется в Google Календарь менеджера.
   - Клиент получает подтверждение записи на электронную почту или через мессенджер.

---

## Используемые сервисы

### 1. **Qwen**
   - Платформа Qwen используется для создания системного промпта и формирования базы знаний.
   - Промпт разработан таким образом, чтобы ассистент мог эффективно обрабатывать запросы клиентов и предоставлять точные ответы.
   - База знаний содержит структурированную, размеченную информацию о компании, услугах и процессах.

### 2. **Савви (Suvvy.ai)**
   - Сервис Suvvy.ai применяется для создания и настройки ИИ-ассистента.
   - Платформа предоставляет инструменты для интеграции ассистента с различными каналами коммуникации (сайт, мессенджеры, CRM).
   - Поддерживает автоматизацию процессов, таких как запись на звонок и интеграция с Google Календарем.

---

## Преимущества проекта

1. **Автоматизация рутинных задач**  
   Ассистент берет на себя обработку стандартных запросов, что позволяет сотрудникам сосредоточиться на более сложных задачах.

2. **Повышение конверсии**  
   Благодаря персонализированному подходу и своевременному сопровождению клиентов, увеличивается вероятность успешного завершения сделки.

3. **Улучшение качества обслуживания**  
   Клиенты получают быстрые и точные ответы на свои вопросы, что повышает уровень их удовлетворенности.

4. **Гибкость и масштабируемость**  
   Решение легко адаптируется под изменяющиеся потребности компании и может быть расширено для поддержки дополнительных функций.

---

## Этапы реализации

1. **Анализ требований**  
   Изучение бизнес-процессов компании и определение ключевых задач для ассистента.

2. **Разработка базы знаний**  
   Создание структурированной базы знаний с использованием Qwen.

3. **Настройка ассистента**  
   Конфигурация ИИ-ассистента в Suvvy.ai, включая создание промптов и интеграцию с Google Календарем.

4. **Тестирование**  
   Проведение тестовых диалогов для проверки корректности работы ассистента и устранения возможных ошибок.

5. **Запуск и внедрение**  
   Развертывание ассистента на сайте компании и в мессенджерах.

6. **Поддержка и доработка**  
   Мониторинг работы ассистента, сбор обратной связи от клиентов и внесение улучшений.

---

## Заключение
ИИ-ассистент для строительной компании — это современное решение, которое поможет автоматизировать взаимодействие с клиентами, повысить эффективность работы отдела продаж и улучшить качество обслуживания. Благодаря использованию передовых технологий и интеграции с популярными сервисами, проект станет надежным инструментом для развития бизнеса.


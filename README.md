<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Минималистичный Лендинг с Кейcами</title>
  <style>
    body {
      background: #fafbfc;
      color: #222;
      font-family: 'Inter', 'Segoe UI', Arial, sans-serif;
      margin: 0;
      padding: 0;
      font-size: 18px;
      line-height: 1.6;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .page-title {
      font-size: 2.5rem;
      font-weight: 700;
      margin-bottom: 0.3em;
      letter-spacing: -0.02em;
    }
    .page-subtitle {
      font-size: 1.25rem;
      color: #666;
      margin-bottom: 2.5em;
      font-weight: 400;
    }
    .case {
      display: flex;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.03);
      overflow: hidden;
      margin-bottom: 40px;
      transition: box-shadow 0.2s;
    }
    .case:hover {
      box-shadow: 0 4px 24px rgba(0,0,0,0.07);
    }
    .case-col-1 {
      flex: 1;
      min-width: 0;
      background: #f6f7f9;
      padding: 32px 24px;
      font-weight: 500;
      border-right: 1px solid #ececec;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .case-col-2 {
      flex: 2;
      min-width: 0;
      padding: 32px 32px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    .case-title {
      font-size: 1.25rem;
      font-weight: 600;
      margin-bottom: 0.5em;
    }
    .case-subtitle {
      font-size: 1rem;
      color: #888;
      margin-bottom: 1.5em;
    }
    .divider {
      border: none;
      border-top: 1.5px solid #ececec;
      margin: 40px 0;
    }
    @media (max-width: 700px) {
      .case {
        flex-direction: column;
      }
      .case-col-1, .case-col-2 {
        border-right: none;
        padding: 24px 16px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="page-title">Наши кейсы</div>
    <div class="page-subtitle">Реальные истории успеха и внедрения наших решений</div>
    
    <!-- Кейс 1 -->
    <div class="case">
      <div class="case-col-1">
        <div class="case-title">Кейс: Автоматизация документооборота</div>
        <div class="case-subtitle">Клиент: Финансовая компания</div>
      </div>
      <div class="case-col-2">
        <p>
          Внедрили цифровую платформу для автоматизации документооборота. Сократили время обработки документов на 60%, уменьшили количество ошибок и повысили прозрачность процессов.
        </p>
        <ul>
          <li>Интеграция с CRM и 1С</li>
          <li>Обучение персонала</li>
          <li>Поддержка и сопровождение</li>
        </ul>
      </div>
    </div>
    <hr class="divider">

    <!-- Кейс 2 -->
    <div class="case">
      <div class="case-col-1">
        <div class="case-title">Кейс: Разработка корпоративного портала</div>
        <div class="case-subtitle">Клиент: Производственная компания</div>
      </div>
      <div class="case-col-2">
        <p>
          Создали современный корпоративный портал для сотрудников компании. Решение объединило внутренние сервисы, повысило вовлечённость и ускорило коммуникацию между отделами.
        </p>
        <ul>
          <li>Единая точка входа</li>
          <li>Мобильная версия</li>
          <li>Интеграция с Active Directory</li>
        </ul>
      </div>
    </div>
    <hr class="divider">

    <!-- Кейс 3 (пример для масштабирования) -->
    <div class="case">
      <div class="case-col-1">
        <div class="case-title">Кейс: Внедрение BI-аналитики</div>
        <div class="case-subtitle">Клиент: Ритейл-сеть</div>
      </div>
      <div class="case-col-2">
        <p>
          Реализовали систему BI-аналитики для мониторинга продаж и складских остатков в реальном времени. Руководство получило прозрачную аналитику и инструменты для принятия решений.
        </p>
        <ul>
          <li>Дашборды Power BI</li>
          <li>Сбор данных из ERP и POS</li>
          <li>Настройка алертов</li>
        </ul>
      </div>
    </div>
    <hr class="divider">

    <!-- Добавляйте новые кейсы ниже по аналогии -->
  </div>
</body>
</html>


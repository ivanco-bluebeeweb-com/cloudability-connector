# Apptio Cloudability Connector — Connector Discovery

**Vendor API Baseline:** https://cloudability.com

## Архитектура API
- **Базовый адрес:** `https://api.cloudability.com/v3`
- **Протокол:** REST / HTTPS (JSON)
- **Аутентификация:** API Key (Basic Auth: <api_key>:)
- **Ключевые эндпоинты:**
  - отчеты о затратах (/reporting)
  - рекомендации по инстансам (/recommendations)
  - счета вендоров (/vendors)
- **Тестовая точка проверки подключения:** `GET /v3/reporting/reports`.

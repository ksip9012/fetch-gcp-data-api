# fetch-gcp-data-api

GCP 関係の API からデータ取得するためのコード

---

## 以下の各種 API からデータ取得する

- [Reporting API v4](https://developers.google.com/analytics/devguides/reporting/core/v4?hl=ja)
  - Universal Analytics の API
- [Analytics Data API](https://developers.google.com/analytics/devguides/reporting/data/v1?hl=ja)
  - GA4 の API
- [Search Console API](https://developers.google.com/webmaster-tools?hl=ja)
  - Search Console の API

## 構築環境

- [mise](https://mise.jdx.dev/)
- [python](https://www.python.org/)
- [poetry](https://python-poetry.org/)

## Requirement

### Python

- Python==3.12.1

### Packages

- python-dotenv==1.0.1
- padas==2.2.0
- Google 関係
  - google-auth==2.27.0
  - google-api-python-client==2.116.0
  - google-analytics-data==0.18.4
- Linter 関係
  - ruff==0.2.1
  - pandas-stubs==2.1.4.231227
  - google-auth-stubs==0.2.0
  - google-api-python-client-stubs==1.24.0

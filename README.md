# ETL資料分析實做

**主題：上市櫃公司在ESG社會責任和永續發展分析**

抓取資料來源：[台灣證券交易所API](https://openapi.twse.com.tw/)

![image](https://github.com/hank1224/stock-analysis-pipline/blob/main/.github/img/pipline.jpg)

**▼實作課程目標第二項**

![image](https://github.com/hank1224/stock-analysis-pipline/blob/main/.github/img/goal.jpg)

## BI呈現圖

![image](https://github.com/hank1224/stock-analysis-pipline/blob/main/.github/img/BI_2.jpg)

![image](https://github.com/hank1224/stock-analysis-pipline/blob/main/.github/img/BI_3.jpg)

## Defult admin account and port
1. Airbyte:
    - port: 8000
    - username: airbyte
    - password: password

2. Metabase:
    - port: 3000
    - username: None
    - password: None

3. OpenMetadata:
    - port: 8585
    - username: admin
    - password: admin
        - **Airflow:**
        - port: 8080
        - username: admin
        - password: admin

## Note

docker compose specify file
```bash
docker-compose -f YOUR-FILE.yml up
```

## Docker Setup Document Reference
- [Airbyte](https://docs.airbyte.com/deploying-airbyte/local-deployment)
- [Metabase](https://www.metabase.com/docs/latest/installation-and-operation/running-metabase-on-docker)
- [OpenMetadata](https://docs.open-metadata.org/v1.2.x/deployment/docker)

# Projeto Laura - Monitoramento Preditivo de Sepse 🩺

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![Area](https://img.shields.io/badge/Focus-HealthTech%20%7C%20Data-green?style=for-the-badge)

## 📋 Descrição
O **Projeto Laura** é uma assistente virtual inteligente desenvolvida em Python, inspirada na tecnologia de análise de dados hospitalares. O foco principal é a simulação de um sistema de **identificação precoce de riscos clínicos**, cruzando dados e sinais vitais para alertar sobre possíveis quadros de sepse.

---

## 🚀 Demonstração de Fluxo
Aqui está uma representação do processamento de dados e interação da Laura:

```bash
[SISTEMA] Iniciando Motor de Análise Laura...
[VOZ] "Aguardando dados do paciente ou comando de voz..."
[INFO] Cruzando sinais vitais (Temp: 38.5°C, FC: 110bpm)
[ALERT] ALERTA DE RISCO: Padrão compatível com Score de Sepse elevado.
## 🖥️ Demonstração de Execução

Aqui está um exemplo do motor da Laura processando dados em tempo real no terminal:

```bash
# Iniciando o motor de análise Laura...
$ python main.py

[INFO] Conectando ao Banco de Dados... OK
[INFO] Carregando modelo de Inteligência Artificial... OK
[INFO] Escaneando novos sinais vitais...

[ALERT] Paciente ID: 402 - Alteração detectada:
       > Frequência Cardíaca: 115 bpm (↑)
       > Temperatura: 38.5°C (↑)
       > Score de Risco: 0.82 (ALTO)
[ACTION] Notificação enviada para a equipe médica.

## 📊 Análise de Dados e Insights
O sistema utiliza o cruzamento de variáveis críticas. Durante os testes, observamos que:
* A **Temperatura** acima de 38°C combinada com **Frequência Cardíaca** elevada aumentam o Score de Risco em 60%.
* O modelo de **Machine Learning** (Random Forest) foi escolhido pela sua alta precisão em evitar "falsos negativos" em ambientes hospitalares.

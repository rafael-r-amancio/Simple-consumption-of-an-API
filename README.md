
[Portuguese]
Descrição

Este projeto é um script Python que coleta dados meteorológicos de uma cidade específica por uma semana. Os dados são obtidos do serviço VisualCrossing Weather.

Como usar

Para usar o script, siga estas etapas:

Instale as bibliotecas necessárias:
pip install pandas

Obtenha uma chave de API da VisualCrossing Weather.
https://www.visualcrossing.com/

Modifique a variável key no script para a sua chave de API.

Execute o script:

python main.py

O script criará uma pasta chamada semana=<data_inicio> no diretório atual. Dentro dessa pasta, serão criados três arquivos CSV:

dados_brutos.csv: contém todos os dados meteorológicos fornecidos pelo serviço VisualCrossing Weather.
temperaturas.csv: contém as temperaturas mínimas, máximas e atuais para cada dia.
condicoes.csv: contém as condições meteorológicas (descrição e ícone) para cada dia.


[English]
Description

This project is a Python script that collects weather data for a specific city for a week. Data is obtained from the VisualCrossing Weather service.

How to use

To use the script, follow these steps:

Install the required libraries:
pip install os
pip install pandas

Get a VisualCrossing Weather API key.
https://www.visualcrossing.com/

Change the key variable in the script to your API key.

Run the script:

python main.py

The script will create a folder called week=<start_date> in the current directory. Within this folder, three CSV files will be created:

raw_data.csv: contains all weather data provided by the VisualCrossing Weather service.
temperatures.csv: contains the minimum, maximum and current temperatures for each day.
conditions.csv: contains the weather conditions (description and icon) for each day.

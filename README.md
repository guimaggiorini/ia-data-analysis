# Checkpoint 01 – Análise de Dados de Consumidores de Energia

Este projeto contém as resoluções dos exercícios propostos no **Checkpoint 01**, divididos em 4 partes:

1. **Parte 1 e 2** – Análises com o dataset *Individual Household Electric Power Consumption*.  
2. **Parte 3** – Análises com o dataset *Appliances Energy Prediction*.  
3. **Parte 4** – Exercícios no **Orange Data Mining**.

Todas as respostas estão documentadas no arquivo Jupyter Notebook (`IA.ipynb`).
Os gráficos são gerados dentro do notebook e as **respostas às perguntas** aparecem ao final de cada bloco de código, no formato:

```
# Exercício X

(resolução aqui)

# Pergunta: XXXX?
# Resposta: XXXX
```

Os exercícios que não pedem para gerar algum código estão em blocos de texto. O arquivo Jupyter Notebook segue a ordem dos exercícios. 

---

## Integrantes do grupo

* Arthur Vieira Mariano – RM554742
* Guilherme Henrique Maggiorini – RM554745
* Ian Rossato Braga – RM554989

---

## Estrutura do projeto

```
/
├── IA.ipynb               # Notebook principal com todos os exercícios
├── README.md              # Este arquivo
├── orange/                # Imagem do fluxo do Orange Data Mining
└── data/                  # Datasets utilizados
````

O arquivo `IA.ipynb` também pode ser encontrado no Google Colab clicando [AQUI](https://colab.research.google.com/drive/1Ns47q5HQ7yhevUwV7e0QR5pyNFka0_46?usp=sharing).

---

## Datasets utilizados

### 1. Individual Household Electric Power Consumption  
- **Fonte:** UCI Machine Learning Repository  
- **Formato:** `.txt`, separado por `;`  
- **Período:** dezembro de 2006 até novembro de 2010, com leituras a cada minuto.  
- **Principais variáveis:**
  - `Global_active_power` – potência ativa global (kW)  
  - `Global_reactive_power` – potência reativa global (kW)  
  - `Voltage` – tensão (V)  
  - `Global_intensity` – corrente global (A)  
  - `Sub_metering_1/2/3` – medições de subcircuitos (Wh)  

### 2. Appliances Energy Prediction  
- **Fonte:** UCI Machine Learning Repository  
- **Formato:** `.csv`  
- **Registros:** 29.304 observações em intervalos de 10 minutos  
- **Principais variáveis:**
  - `Appliances` – consumo energético dos eletrodomésticos (Wh)  
  - `lights` – consumo das luzes (Wh)  
  - `T1` ... `T9` – temperaturas em diferentes cômodos (°C)  
  - `RH_1` ... `RH_9` – umidade relativa em diferentes cômodos (%)  
  - `T_out`, `RH_out` – condições externas  
  - `Windspeed`, `Visibility`, `Tdewpoint`, `rv1`, `rv2` – variáveis adicionais  

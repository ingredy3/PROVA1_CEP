# 📊 Controle Estatístico de Processo (CEP) — Prova 1

Este repositório contém a implementação de **Cartas de Controle X̄ e R** para monitoramento estatístico de um processo de produção, desenvolvido como parte da disciplina de **Controle Estatístico de Processos (CEP)**.

## 📌 Descrição do Projeto

O projeto aplica técnicas de controle estatístico para monitorar a estabilidade de um processo de fabricação utilizando:
- **Carta de Controle X̄ (Médias)**
- **Carta de Controle R (Amplitudes)**

Foram utilizados **25 subgrupos com 5 medições cada**, totalizando 125 observações extraídas do dataset `Manufacturing_dataset.csv`.

## 🧩 Estrutura do Notebook

1. **Configuração e Importação de Bibliotecas**
2. **Carregamento dos Dados** (via GitHub)
3. **Preparação dos Dados** no formato 25×5
4. **Cálculo das Estatísticas** (X̄ e R por amostra)
5. **Cálculo dos Limites de Controle**
6. **Plotagem das Cartas de Controle X̄ e R**
7. **Análise dos Resultados**

## 📈 Resultados Obtidos

### Estatísticas Globais:
- **Média das Médias (X̄̄):** 74,7958
- **Média das Amplitudes (R̄):** 4,5540

### Limites de Controle (n = 5):
#### Carta X̄:
- **LC:** 74,7958 | **LIC:** 72,1682 | **LSC:** 77,4235

#### Carta R:
- **LC:** 4,5540 | **LIC:** 0,0000 | **LSC:** 9,6272

### Conclusão:
✅ **Processo sob controle estatístico** — todas as amostras dentro dos limites, sem padrões anormais.

## 🛠 Tecnologias Utilizadas

- **Python 3**
- **Pandas, NumPy, Matplotlib**
- **Jupyter Notebook / Google Colab**

## 👨‍🎓 Autor

**Ingredy Thamis**  
Disciplina: Controle Estatístico de Processos

---

*Projeto desenvolvido para fins educacionais.*

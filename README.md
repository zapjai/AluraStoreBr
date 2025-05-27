# 📊 Challenge Data Science - Análise de Dados das Lojas 

## Objetivo
Este projeto analisa o desempenho de 4 lojas para identificar qual delas deve ser vendida, considerando múltiplos fatores estratégicos como faturamento, satisfação do cliente e custos operacionais.

## 📌 Visão Geral
Análise completa das operações de quatro lojas, incluindo:

- 💰 Faturamento total
- 🏷️ Desempenho por categoria de produtos
- ⭐ Avaliação dos clientes
- 📦 Custo médio de frete
- 🏆 Produtos mais e menos vendidos

## 🔍 Principais Descobertas

### Performance Comparativa
| Métrica          | Loja 1 | Loja 2 | Loja 3 | Loja 4 |
|------------------|--------|--------|--------|--------|
| Faturamento (R$) | 1.25M  | 1.10M  | 1.40M  | 0.95M  |
| Avaliação (1-5)  | 4.3    | 4.1    | 4.5    | 3.8    |
| Frete Médio (R$) | 35.72  | 44.40  | 36.10  | 52.10  |

### Insights Chave
1. **Loja 3** apresenta o melhor desempenho geral
2. **Loja 4** tem os piores indicadores em todas as métricas
3. Eletrônicos representam 45% do faturamento total

## 📈 Visualizações Principais
Incluímos gráficos interativos que mostram:
- Comparativo de faturamento por loja
- Distribuição de vendas por categoria
- Mapa de calor de desempenho por produto

## 🧠 Recomendação
**Vender a Loja 4** devido a:
- Baixo faturamento
- Avaliações ruins dos clientes
- Custos logísticos elevados
- Desempenho fraco em categorias estratégicas

## 🛠️ Como Usar
1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/analise-lojas.git
```
2. Instale as dependências
```bash
pip install -r requirements.txt
```
3. Execute o notebook Jupyter
```bash
jupyter notebook analise_lojas.ipynb
```

## 📂 Estrutura do Projeto
```
analise-lojas/
├── ChallengeAlura_1.ipynb:                     # Notebook principal com toda a análise e visualizações.         
├── Gráficos: Barra, Linhas, colunas e pizza    # Resultados e visualizações
├── analise_lojas.ipynb                         # Notebook com a análise completa
└── README.md                                   # Este arquivo
```
## 🧰 Tecnologias Utilizadas
Python 3
Pandas
Matplotlib
Seaborn
Jupyter Notebook

## 🤝 Contribuição
Contribuições são bem-vindas! Siga estes passos:
1. Faça um fork do projeto
2. Crie sua branch (`git checkout -b feature/nova-analise`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova métrica'`)
4. Push para a branch (`git push origin feature/nova-analise`)
5. Abra um Pull Request


📌 Observações

Os dados foram disponibilizados pela Alura como parte de um desafio de ciência de dados, com o objetivo de avaliar a capacidade de análise, interpretação e visualização de informações.
O enfoque principal está em transformar dados brutos em insights claros e acionáveis, utilizando técnicas de visualização que facilitem a compreensão e a tomada de decisões.

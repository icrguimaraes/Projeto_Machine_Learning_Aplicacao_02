# Projeto de Machine Learning Aplicado 2  
## Classificação de Sementes de Cacau com CNNs e SVM

Este repositório contém o trabalho desenvolvido para a disciplina **Machine Learning Aplicado 2** da Universidade do Estado do Amazonas (UEA).

##  Objetivo
Propor, implementar e avaliar pipelines de classificação multiclasse para imagens de sementes de cacau no teste de corte, utilizando:
- CNNs pré-treinadas como extratoras de características (Transfer Learning)
- Máquinas de Vetores de Suporte (SVM) como classificadores
- Estratégias de ensemble (Stacking e Soft Voting)

## 📊 Dataset
- **An image dataset of cut-test-classified cocoa beans**  
- Santos et al. (2019)  
- Aproximadamente 1.400 imagens organizadas por classe

##  Metodologia
- CNNs com pesos congelados (ImageNet)
- Extração de vetores de características
- Normalização com StandardScaler
- Classificação com SVM
- Grid Search para ajuste de hiperparâmetros
- Avaliação com acurácia, precisão, recall e F1-score
- Análise comparativa e matrizes de confusão

##  Estrutura do Repositório
- `notebooks/`: Notebook principal do projeto
- `figures/`: Gráficos e visualizações geradas
- `results/`: Resultados tabulados
- `references/`: Artigos e materiais de apoio

##  Referências
- Santos, F. et al. (2019)
- Malcher, D. & Guedes, E. (2022)
- Sarkar, D. et al. (2018)

---

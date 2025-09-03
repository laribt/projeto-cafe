## Projeto 
Modelagem de dados para autenticação de cafés do Cerrado Mineiro: avaliação sazonal e diferenciação geográfica

## ☕️ Autenticação de café

Desenvolvimento de modelos quimiométricos (PCA/HCA, KNN e SVM) aplicados a espectros UV–Vis para diferenciar cafés do Cerrado Mineiro de outras regiões e avaliar possíveis efeitos sazonais. O foco é mostrar um pipeline claro e reproduzível da extração, pré-processamento e exploração, até a classificação e avaliação.

## 🎯 Objetivos
- Caracterizar perfis espectrais UV–Vis de amostras de café.
- Investigar sazonalidade (safras) via PCA.
- Diferenciar Cerrado Mineiro vs. Outras regiões com PCA/HCA (exploratório) e KNN/SVM (supervisionado).
- Tratar desbalanceamento com ADASYN e comparar resultados.

## 🧰 Tecnologias & Ferramentas
- **Linguagem**: Python (3.10+)
- **Ciência de Dados**: `numpy`, `pandas`, `scikit-learn`, `matplotlib`
- **Quimiometria**: PCA, HCA, KNN, SVM, ADASYN
- **Editor**: VS Code

## 📊 Resultados 

- PCA evidencia tendência de separação entre regiões.
- KNN + ADASYN melhora especificidade sem perder demasiada sensibilidade.
- SVM apresenta boa generalização no conjunto de teste.

## 💡 Conclusões

- A integrar Excel + Python (com pandas/openpyxl) em um fluxo reprodutível.
- Que pré-processamento (centragem/normalização e seleção de faixa) muda o jogo em espectroscopia.
- PCA/HCA direciona decisões antes do supervisionado (KNN/SVM).
- É mportantede tratar desbalanceamento (e validar no teste para não superestimar). 


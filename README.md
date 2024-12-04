### README do Projeto: Previsão de Rostos  

#### **Descrição do Projeto**  
Este projeto utiliza redes neurais convolucionais (CNNs) para classificar imagens faciais como masculinas ou femininas. Ele explora técnicas como pré-processamento de imagens (conversão para preto e branco, *data augmentation*) e ajuste de hiperparâmetros. O desempenho é avaliado com métricas como acurácia, F1-Score e AUC-ROC.  

---

#### **Configurações Necessárias**  

- **Versão do Python**: 3.8 ou superior  
- **Bibliotecas**:  
  - `tensorflow`  
  - `numpy`  
  - `matplotlib`  
  - `pandas`  
  - `keras-tuner`  

---

#### **Dataset Utilizado**  
O projeto utiliza o **CUHK Face Sketch Database (CUFS)**, disponível no [Kaggle](https://www.kaggle.com/).  

---

#### **Execução no Google Colab**  

1. **Abrir o Notebook**  
   - Acesse o Google Colab e carregue o arquivo `Restic36_CD_P10.ipynb` (via link ou upload).  

2. **Instalar Dependências**  
   - Execute a célula destinada à instalação das bibliotecas.  

3. **Executar o Notebook**  
   - Siga a ordem das células para treinar e avaliar o modelo.  

---

#### **Resultados e Análises**  

- **Melhor Desempenho**:  
  - Imagens convertidas para preto e branco obtiveram os melhores resultados.  

- **Impacto do *Data Augmentation***:  
  - Menor do que o esperado, enquanto o pré-processamento foi mais determinante.  

- **Análise de Erros**:  
  - Mulheres com cabelos curtos e crianças apresentaram maior taxa de erros devido ao desequilíbrio de classes.  

---

#### **Desafios e Limitações**  

1. **Desequilíbrio de Classes**  
   - Número desigual de imagens masculinas e femininas impactou o modelo.  

2. **Simplicidade da Arquitetura**  
   - Arquitetura básica foi proposital, mas pode ser aprimorada com técnicas como *Dropout* e *Batch Normalization*.  

---

#### **Próximos Passos**  

1. **Aprimoramento da Arquitetura**  
   - Testar modelos avançados como *ResNet* e *EfficientNet*.  

2. **Expansão do Dataset**  
   - Incluir conjuntos mais variados e balanceados.  

3. **Técnicas Avançadas**  
   - Aplicar equalização de histograma e *Grad-CAM* para maior interpretabilidade.  

---

#### **Autores**  

- Saulo Alves 
- Thailane Carmo 

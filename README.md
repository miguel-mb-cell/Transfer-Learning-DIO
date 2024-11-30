# Transfer Learning com VGG16 🧠 e Dataset de Cães e Gatos🐶🐱 

Bem vindo ao meu estudo sobre Transfer Learning! 📚

Neste estudo é usada a rede [VGG16](https://keras.io/api/applications/vgg/#vgg16-function) do Keras.
<div align="center">
  <img src="/imgs/estrutura_vgg16.png" alt="Arquitetura VGG16" height=500px width=650px/>
</div>
<br>
Usando a técnica de Transfer Learning para treinar uma nova rede para classificar um dataset de cães e gatos!
<br><br>
<div align="center">
  <img src="/imgs/dataset.png" alt="Dataset"  height=500px width=650px/>
</div>

## 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/-Python-333?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white)

### Stack de Tecnologias

1. **Linguagem de Programação:**
   - ![Python](https://img.shields.io/badge/-Python-333?style=flat&logo=python&logoColor=white) Python

2. **Bibliotecas e Frameworks:**
   - ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) TensorFlow
   - ![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat&logo=keras&logoColor=white) Keras
   - ![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat&logo=numpy&logoColor=white) NumPy
   - ![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white) Matplotlib

### Outras Ferramentas

- ![Colab](https://img.shields.io/badge/-Google%20Colab-F9AB00?style=flat&logo=google-colab&logoColor=white) para desenvolvimento e execução do notebook.

## 📑 Tópicos Abordados

1. **🎯 Objetivo**
   - Explicar o propósito do estudo e os resultados esperados.

2. **📝 Procedimento**
   - Descrever o que foi feito durante o estudo.

3. **🔄 O que é Transfer Learning**
   - Definição e benefícios da técnica de Transfer Learning.

4. **📥 Importações necessárias para o estudo**
   - Listar as bibliotecas e pacotes importados para o estudo.

5. **📂 Preparando o dataset**
   - Detalhes sobre a preparação e manipulação do conjunto de dados.

6. **🧠 O modelo VGG16**
   - Introdução à arquitetura do modelo VGG16.

7. **🏗️ Como funcionam as camadas**
   - Explicação sobre as camadas da rede VGG16 e suas funções.

8. **♻️ Reaproveitando o modelo VGG16**
   - Como a rede VGG16 foi adaptada para o estudo específico.

9. **📊 Conclusão**
   - Sumário dos principais achados e implicações do estudo.

10. **💻 Teste você mesmo**
    - Passe uma imagem de gato ou cachorro por url para testar o modelo!
>ℹ️ Para poder executar e editar as células do notebook, dentro do arquivo, clique em "Arquivo" na barra de ferramentas e em "Salvar uma cópia no Drive".

12. **📚 Referências**
    - Lista de materiais e fontes utilizados para o estudo.


## 📊 Resultados de Treinamento
Essa tabela é o resultado obtido com o treinamento do novo modelo criado a partir da técnica de **transfer learning** aplicada ao modelo VGG16, para o dataset de cães e gatos.

| Época | Acurácia | Perda   | Val. Acurácia | Val. Perda |
|-------|----------|---------|---------------|------------|
| 1/10  | 0.5505   | 1.1679  | 0.5067        | 0.8510     |
| 2/10  | 0.4775   | 0.8609  | 0.4933        | 0.8893     |
| 3/10  | 0.5035   | 0.7981  | 0.5067        | 0.7553     |
| 4/10  | 0.5279   | 0.7170  | 0.6800        | 0.5827     |
| 5/10  | 0.6403   | 0.6003  | 0.5467        | 0.5882     |
| 6/10  | 0.7054   | 0.5479  | 0.7200        | 0.5319     |
| 7/10  | 0.7256   | 0.5184  | 0.8800        | 0.4713     |
| 8/10  | 0.8633   | 0.4603  | 0.8267        | 0.4799     |
| 9/10  | 0.8372   | 0.4468  | 0.7867        | 0.4261     |
| 10/10 | 0.8582   | 0.4156  | 0.8400        | 0.4085     |

Cerca de **85%** de acurácia!

## 🔍 Confira os detalhes
Confira em detalhes o estudo feito no Google Colab: [Transfer Learning](https://colab.research.google.com/drive/1iAtTVHvMrdut0jFS-CVh09KbLHI5B9xY?usp=sharing).

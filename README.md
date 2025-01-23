# Integration of computer vision and machine learning techniques for drug identification in robotic medicine dispensing systems

# Sistema de Identificação de Medicamentos

Este repositório contém os códigos e recursos do projeto de conclusão de curso de Thiago Cabral Vilar, desenvolvido na residência em Robótica e Inteligência Artificial do CIn-UFPE. O projeto utiliza robôs Kinova para automação na dispensação de medicamentos, combinando técnicas de visão computacional para identificar medicamentos por meio de suas características físicas.

## Estrutura do Repositório

- `extract_features/`: Contém scripts independentes para extração de características dos medicamentos.
- `medicine_identification_script/`: Script que se conecta com o robô Kinova para capturar imagens e identificar medicamentos baseado na largura e área da máscara. Precisa ser conectado aos Kinova.
- `dataset.csv`: Dataset utilizado para treinar os modelos de machine learning.
- `KNN.ipynb`: Análises e resultados dos modelos KNN e Decision Tree(Colab).
- `test1.mp4`: https://youtube.com/shorts/ClpWs_6Oyk8?si=tsNRVHpxdYLcUFnG

## Configuração do Ambiente

Para executar os scripts deste repositório, é recomendado configurar um ambiente Python com as dependências listadas em `requirements.txt`.

```bash
pip install -r requirements.txt

python extract_features/feature_extractor.py

Thiago Cabral Vilar
Email: oceanocabral@gmail.com

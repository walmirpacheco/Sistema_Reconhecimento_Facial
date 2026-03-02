# 🎯 Sistema de Reconhecimento Facial com TensorFlow

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Um sistema completo de reconhecimento facial desenvolvido em Python usando TensorFlow, implementado para funcionar perfeitamente no Google Colab. O sistema utiliza MTCNN para detecção facial e ResNet50 para extração de características (embeddings) faciais.

## 📋 Índice

- [Características](#-características)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura do Sistema](#-arquitetura-do-sistema)
- [Como Usar no Google Colab](#-como-usar-no-google-colab)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Melhorias em Relação ao Código Original](#-melhorias-em-relação-ao-código-original)
- [Limitações e Próximos Passos](#-limitações-e-próximos-passos)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

## ✨ Características

- ✅ **Detecção Facial Robusta**: Utiliza MTCNN para detectar faces com alta precisão, incluindo pontos faciais (olhos, nariz, boca)
- ✅ **Extração de Embeddings**: Usa ResNet50 pré-treinada para gerar representações vetoriais (embeddings) de faces
- ✅ **Classificação Multi-classe**: Reconhece múltiplas pessoas com threshold de confiança ajustável
- ✅ **Interface Interativa**: Menu completo para treinamento e teste no Colab
- ✅ **Persistência de Modelo**: Salva e carrega modelos treinados
- ✅ **Visualização em Tempo Real**: Mostra detecções e reconhecimentos com bounding boxes
- ✅ **Upload de Imagens**: Integração com Google Colab para upload fácil de imagens

## 🛠 Tecnologias Utilizadas

| Tecnologia | Versão | Função |
|------------|--------|---------|
| TensorFlow | 2.x | Framework principal para deep learning |
| MTCNN | - | Detecção facial e pontos faciais |
| ResNet50 | - | Extração de embeddings faciais |
| OpenCV | 4.x | Processamento de imagens |
| Scikit-learn | 1.x | Pré-processamento e métricas |
| Matplotlib | 3.x | Visualização de resultados |
| NumPy | 1.x | Operações numéricas |

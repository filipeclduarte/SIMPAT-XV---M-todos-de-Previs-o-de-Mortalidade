# SIMPAT XV Métodos de Previsão de Mortalidade

## Descrição
Este minicurso apresenta uma introdução aos métodos de previsão de mortalidade, combinando abordagens estatísticas clássicas com técnicas modernas de Deep Learning. O conteúdo foi desenvolvido para profissionais e estudantes de atuária, demografia e ciência de dados.

## Objetivos
- Compreender os fundamentos da modelagem preditiva aplicada à previsão da mortalidade
- Aplicar modelos estatísticos clássicos: ARIMA, ETS e Lee-Carter
- Implementar modelos de Deep Learning: CNN, LSTM e Transformer
- Utilizar métodos de combinação de preditores
- Avaliar a qualidade das previsões com métricas apropriadas
  
## Conteúdo Programático

### 1. Fundamentos da Modelagem Preditiva
- Etapas do processo de modelagem
- Métricas de erro e avaliação

### 2. Modelos Estatísticos
- **ARIMA**: Modelos autoregressivos integrados de médias móveis
- **ETS**: Exponential Smoothing State Space models
- **Lee-Carter**: Modelo demográfico clássico para projeção de mortalidade

### 3. Modelos de Deep Learning
- **CNN**: Redes neurais convolucionais para extração de padrões temporais
- **LSTM**: Long Short-Term Memory para modelagem de dependências de curto e longo prazo
- **Transformer**: Arquitetura baseada em atenção para séries temporais
  
### 4. Combinação de Preditores
- Métodos de ensemble
- Combinando modelos estatísticos e de Deep Learning

### 5. Avaliação de Resultados
- Métricas quantitativas de erro
- Análise comparativa entre modelos

## Dados Utilizados
Os dados utilizados no minicurso são provenientes do **UN Population Division Data Portal**, incluindo tábuas de mortalidade abreviadas de múltiplos países. Os dados foram processados e disponibilizados pelo projeto de extensão **OIAtuarial** da UFPB.

## Autores
- **Filipe Coelho de Lima Duarte**
- **Cleo Decker Anacleto**
- **OIAtuarial** (Universidade Federal da Paraíba)

## Como Usar
### Opção 1: Google Colab (Recomendado)
Clique no badge "Open In Colab" acima para executar o notebook diretamente no Google Colab, sem necessidade de instalação local.

### Opção 2: Execução Local
```bash
# Clone o repositório
git clone https://github.com/filipeclduarte/SIMPAT-XV---M-todos-de-Previs-o-de-Mortalidade.git
# Instale as dependências
pip install pandas numpy matplotlib seaborn scikit-learn torch gdown
# Abra o notebook
jupyter notebook SIMPAT_XV_Métodos_de_Previsão_de_Mortalidade.ipynb
```

## Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## Contato
Para dúvidas ou sugestões, entre em contato através do GitHub ou email dos autores.
---

# BootstrapVariance- Intervalo de Confiança Bootstrap para Variância Populacional

Este repositório contém um projeto que explora o uso do método bootstrap para calcular intervalos de confiança para a variância de populações. O método bootstrap é uma técnica estatística poderosa que utiliza reamostragem para estimar a precisão de estatísticas de amostras, sem a necessidade de suposições paramétricas complexas.

## Conteúdo do Projeto

- **Distribuições**: Análise baseada em duas distribuições principais:
  - Distribuição Normal Padrão ($\mu = 0, \sigma = 1$)
  - Distribuição Exponencial ($\lambda = 1$)

- **Simulação**: Geração de amostras de tamanhos variados (5, 30, 100) para observar o efeito do tamanho amostral nos intervalos de confiança.

- **Método Bootstrap**: Implementação do método bootstrap para estimar a variância amostral, incluindo:
  - Cálculo do estimador pontual
  - Cálculo do erro padrão
  - Construção de intervalos de confiança

## Objetivos

- Demonstrar a aplicação do método bootstrap para estimativas de variância.
- Comparar resultados entre distribuições e diferentes tamanhos de amostra.
- Fornecer um exemplo prático e reprodutível para estudantes e profissionais de estatística.

## Instruções

O código é implementado em R e requer o pacote `EnvStats`. Certifique-se de instalar todas as dependências antes de executar as simulações.

## Contribuição

Contribuições e sugestões são bem-vindas! Sinta-se à vontade para abrir _issues_ ou enviar _pull requests_.

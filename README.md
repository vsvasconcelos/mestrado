# Repositórios dos arquivos utilizados na dissertação de mestrado:PREVISÃO DE DEMANDA NA FASE DE PLANEJAMENTO ANTECIPADO DEPROJETOS DE TRANSPORTE DE PASSAGEIROS: UMA ABORDAGEM PORREDES NEURAIS ARTIFICIAIS
https://bibliotecatede.uninove.br/bitstream/tede/151/1/Vagner%20Sanches%20Vasconcelos.pdf

# Pré-processamento dos dados
O pré-processamento dos dados envolve as etapas de normalização e reagrupamento dos dados. Para realização destas etapas foi desenvolvido o script Geradados.sce no SciLab, o Apêndice A apresenta esse script. Ele foi executado apenas uma vez, e os resultados foram salvos em um formato proprietário (DadosMSc.sod) deste software de forma que sempre foi possível o resgate desses dados.

# Normalização dos Dados
Conforme definido no critério de normalização, o menor valor de cada variável é normalizado no valor 0,100 e o maior no valor 0,900

# Treinamento, teste e validação das RNA
Para realização das etapas de treinamento, teste e validação, foram desenvolvidos os scripts: Treinamento.sce; Teste.sce; e Validacao.sce.
Para gerar os gráficos de dispersão e calcular os coeficientes r e R² da reta de 45º do modelo ideal, foi desenvolvido o script Dispersao.sce no SciLab.

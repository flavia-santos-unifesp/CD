# CD
Circuitos Digitais

**VitalsGuard** **Digital** é um protótipo de circuito digital desenvolvido para a disciplina de Circuitos Digitais da Unifesp/ICT. O projeto visa contribuir para o 
**Objetivo de Desenvolvimento Sustentável (ODS) 3: Saúde e Bem-estar** da ONU, promovendo o monitoramento básico e acessível de sinais vitais.

Ele integra sensores para frequência cardíaca (FC), saturação de oxigênio (SpO2) e temperatura corporal, processando esses dados para gerar um Índice de Saúde e um Alarme Crítico.

**O Desafio**
Parte do Ideathon-CD, o projeto busca uma solução tecnológica inovadora para o ODS 3. A crescente demanda por monitoramento domiciliar de saúde justifica o desenvolvimento de dispositivos acessíveis e integrados.

**Funcionalidades**
O sistema recebe dados de três sensores principais, já em formato digital:

Frequência Cardíaca (FC): Entrada numérica de 5 bits, cobrindo de 40 a 120 bpm.
Saturação de Oxigênio (SpO2): Entrada numérica de 4 bits, cobrindo de 70% a 100%.
Temperatura Corporal: Entrada binária de 1 bit (0 para ≤37,5ºC, 1 para >37,5ºC).

O circuito processa essas informações para gerar:

Índice de Saúde (2 bits): Uma avaliação do risco em quatro níveis: 00 (Saudável), 01 (Alerta), 10 (Risco) e 11 (Crítico).
Alarme Crítico (1 bit): Ativado por qualquer anomalia grave. Quando ativo (1), aciona um LED vermelho e um buzzer.
LEDs Visuais: Indicam o estado geral: Verde (normal), Azul (um sinal alterado), Lilás(dois sinais alterados) e Vermelho (condição crítica).

Um Flip-Flop SR mantém o alarme crítico ativado mesmo após a condição momentânea de risco cessar, exigindo um reset manual.

**Implementação**
O protótipo foi desenvolvido no software WiredPanda. Inclui circuitos lógicos, aritméticos, e componentes sequenciais (Flip-Flops).

**Como Usar (WiredPanda)**
Baixe o arquivo do circuito .wp.

Abra o WiredPanda e carregue o circuito.

Interaja com os Inputs (sensores de FC, SpO2 e Temperatura) para simular diferentes condições de saúde.

Observe as saídas (LEDs de saúde, display do Índice de Saúde e o LED/buzzer do Alarme Crítico).

Utilize o botão de reset para desativar o alarme crítico travado.

**Contribuições**
Caroline Carvalho
Flavia Fernandes
Isabela Diniz Carvalho

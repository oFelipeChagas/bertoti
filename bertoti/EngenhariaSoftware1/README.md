Introdução: No curso de Engenharia de Software, o professor requeriu uma série de exercícios que fazem reflexão a respeito dos trade-offs (balanceamentos/negociação entre tecnologias) que são necessários quando se passa a ser um agente da Tecnologia da Informação. As questões são as que seguem:

1) Observe e comente os dois exertos de uma publicação feita por um funcionário do google a respeito do que é Engenharia de Software: 

"We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play. On a software engineering project, engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth."

Comentário: É necessário considerar os três aspectos que distinguem e conectam a Engenharia de Software da Programação, quais sejam: tempo, escala e saber abrir mão/negociar.

Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software engineering: after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming.

Comentário: É necessário que se saiba vislumbrar onde se quer chegar e saber lidar com as limitações que existem no momento. É sempre importante fazer essas distinções, de modo a criar um método que possa ser revisto de forma clara e atualizada sempre que a tecnologia se oportunizar.

2) Selecione duas tecnologias e compare seus requisitos não funcionais explicando seus trade-offs:

Linguagens de programação - requisito: nível de facilidade/usabilidade para pessoas em geral:
    Para interface humana em que o nível de processamento não necessita ser alto nem extremamente rápido - Python. 
    Para interface humana em que o nível de processamento não necessita ser extremamente fácil, mas precisa estar mais próximo da linguagem de máquina - Java.

Linguagens de programação - portabilidade:
    Para processamento de dados bancários: linguagens baseadas em COBOL, devido ao legado
    Para processamento de dados em geral: C, que pode ou não ter interface com outras linguagens de programação de alto nível, a depender dos trade-offs.

Chip de processamento:
    Para portaria: Intel Pentium 
    Para clima: BullSequana XH3000 da Eviden - Supercomputador climático sediado em Petrópolis, chamado de Santos Dumont

3) Observe a imagem e faça um comentário:

![Realação processamento-consumo energético](https://github.com/user-attachments/assets/0c1c8816-ce8d-44aa-9d01-d908c8571dc2)

Legenda da imagem, feita por Alex Xu em uma postagem x: "The study below runs 10 benchmark problems in 28 languages. It measures the runtime, memory usage, and energy consumption of each language. The abstract of the paper is shown below."

Comentário: A presente imagem faz uma correlação entre consumo de energia e capacidade de processamento. Esse é um dos trade-offs que devem ser levados em consideração quando se usa uma aplicação de processamento em larga escala. Uma vez que, por vezes, compensa muito mais fazer o processamento bruto em Linguagens mais próximas à linguagem de máquina e deixar as linguagens mais afastadas do hardware como interface humano máquina, reduzindo o custo operacional, o gasto energético e, frequentemente, o tempo gasto para o processamento final. Saber a resposta de por quê optar por uma ou outra tecnologia é a habilidade que se espera desenvolvida em um analista de sistemas. 
    

# prova2computacaonuvem

## 1. Fundamentos da Computação em Nuvem

Questão 1. Qual é a diferença entre IaaS e SaaS? Cite um exemplo de utilização de cada modelo. 

Resposta:

IaaS é Infraestrutura como Serviço, ou seja, uma empresa contrata uma infraestrutura em Cloud para cuidar das questões da infraestrutura. Ex.: AWS
SaaS é Softwate como Serviço, ou seja, uma empresa contrata uma Software em Cloud para utilizar os serviços de um software. Ex.: Canva.

A Diferenças entre eles é quanto mais próximo de SaaS menos responsável pela aplicação mais "trabalho".



Questão 2. Uma empresa utiliza servidores próprios e também recursos de um provedor de nuvem pública. Qual modelo de implantação em nuvem essa empresa utiliza?

Resposta:

O modelo é Hibrido



Questão 3. Qual é a principal diferença entre uma máquina virtual e um contêiner? Responda com suas próprias palavras, utilizando os conhecimentos trabalhados nas aulas.

Resposta:

Uma Maquina Virtual utiliza Tudo que uma ISO tem, Por exemplo Uma maquina virtual terá a câmera do Windows, Perfeito para um ambiente de HML
Já um contêiner utilizará apenas o que for necessario para desenvolvimento de uma produto.

## 6. Interpretação dos Resultados

Questão 1. Qual é a diferença entre uma imagem docker e um contêiner em execução?

Resposta:

Uma Imagem docker é a planta de onde o Contêiner será criado, Já o Contêiner é a instancia em sí funcionando em segundo plano, seria como uma casa pronta.

Questão 2. Qual é a função de um Deployment no Kubernetes?

Resposta:

Ele é como o cara que faz os Pods continuarem de Pé, um Exemplo seria, quando um pod apresenta falha, ele reinicia uma nova instancia de pod para suprir o pod que caiu assim, voltando ao padrão especificado.

Questão 3. O que aconteceu quando você excluiu um Pod? Por que isso aconteceu?

Resposta:

Ele foi "recuperado", na verdade subiu outro pod, isso acontece porque fizemos um deployment com 3 replicas

Questão 4. Qual é a finalidade de um Service no Kubernetes?

Resposta:

O Service é quem cria o acesso a comunicação HTTP dentro do cluster Kubernetes.


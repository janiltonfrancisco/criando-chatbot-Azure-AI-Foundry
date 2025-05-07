*Chatbot Baseado em Conteúdo de PDFs no ambiente Azure IA Foundry*

.Chatbot Interativo com PDFs usando IA Generativa

--Visão Geral

Este projeto desenvolve um chatbot inteligente que responde perguntas com base em arquivos PDF. Utilizando embeddings e buscas vetorizadas, o sistema consegue entender, estruturar e processar informações extraídas diretamente dos documentos, proporcionando respostas contextuais e relevantes.

O primeiro documento inserido trata da História de Pernambuco, permitindo que o chatbot forneça respostas detalhadas sobre eventos históricos, cultura, expressões regionais e desenvolvimento da região.

--Arquitetura do Projeto

. A implementação segue os seguintes componentes: 

🔹 IA Generativa – Utilização de modelos avançados para interpretar e gerar respostas naturais.

🔹 Embeddings – Transformação do conteúdo dos PDFs em representações matemáticas para facilitar a busca semântica.

🔹 Busca Vetorizada – Algoritmo que encontra respostas baseadas na similaridade de contexto entre perguntas e o conteúdo extraído.

🔹 Azure AI Foundry – Plataforma utilizada para implementar e escalar o sistema na nuvem.


--Como Funciona

1️⃣ Upload de PDFs – Os usuários inserem documentos contendo conhecimento relevante. 

2️⃣ Processamento dos Arquivos – O sistema converte os textos em embeddings para criar um banco de dados vetorizado. 

3️⃣ Interação via Chat – O usuário faz perguntas e o chatbot busca a resposta diretamente no conteúdo dos PDFs. 

4️⃣ Retorno de Respostas Personalizadas – O chatbot responde com base nos documentos, sem depender apenas de modelos gerais de IA.


--Aplicações Práticas

✅ Consultas Históricas – O chatbot pode responder perguntas sobre eventos, personagens e cultura de Pernambuco. 

✅ Assistente Educacional – Pode ser usado por estudantes e pesquisadores para encontrar informações de forma interativa. 

✅ Suporte Institucional – Empresas podem utilizar para automatizar respostas com base em suas documentações internas. 

✅ Treinamento Interno – Organizações podem integrar novos funcionários com um chatbot treinado em materiais específicos.

--Algumas etapas importantes na criação do projeto:

A figura abaixo exibe os primeiros passos, a criação do Hub e escolher o recurso:

![Image](https://github.com/user-attachments/assets/723dc6be-d452-4a70-be6d-df28cf10b7a8)

A seguir podemos observar a criação do projeto, dentro do laboratório AI Foundry. Podemos observar a API KEY, endpoint, menu playground:

![Image](https://github.com/user-attachments/assets/d5fa1a45-f068-4f1b-9069-d51561c5c9a3)

No playground podemos implantar os modelos de IAs:

![Image](https://github.com/user-attachments/assets/21fd9755-3173-40d6-ae92-c5bdc8c42bd7)
![Image](https://github.com/user-attachments/assets/2268fc7b-4ab3-4ab3-a4e5-2319b8eb6f9a)


Ainda no playground do chat, podemos fazer o upload dos dados escolhidos, no caso, o PDF com a história de Pernambuco:

![Image](https://github.com/user-attachments/assets/28a3e0c4-9d89-4589-89ef-c469df2e108b)

Projeto finalizado, após inserir o PDF e adicionar o Azure AI Search( irá buscar o contexto no texto, já dividido em vetores):

![Image](https://github.com/user-attachments/assets/cd508d74-858f-4f2e-9a2c-fd1b060a5dfa)




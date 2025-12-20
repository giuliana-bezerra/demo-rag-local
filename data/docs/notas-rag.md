# RAG - Retrieval-Augmented Generation

RAG (Retrieval-Augmented Generation) é um padrão arquitetural que combina
modelos de linguagem com mecanismos de busca em bases de conhecimento.

Ao invés de depender apenas do conhecimento pré-treinado do modelo, o RAG
recupera informações relevantes de uma base externa e as utiliza como contexto
para gerar respostas.

## Como funciona o RAG

O fluxo básico de um sistema RAG envolve:

1. Transformar documentos em vetores (embeddings)
2. Armazenar esses vetores em um banco vetorial
3. Converter a pergunta do usuário em embedding
4. Buscar documentos semanticamente similares
5. Enviar o contexto recuperado para o modelo de linguagem

## Benefícios do RAG

- Redução de alucinações do modelo
- Uso de dados atualizados e específicos
- Maior controle sobre as fontes de informação
- Melhor explicabilidade das respostas

## RAG Local

Em um RAG local, tanto o modelo de linguagem quanto o banco vetorial são
executados no ambiente local ou on-premises.

Esse modelo é especialmente útil em cenários que exigem:
- Privacidade de dados
- Compliance regulatório
- Controle de custos
- Governança sobre informações sensíveis

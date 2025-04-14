# Análise de Sentenças com IA 🤖📝

## Descrição do Projeto

Este projeto tem como objetivo utilizar uma Inteligência Artificial para analisar um conjunto diversificado de sentenças. O intuito é extrair insights sobre padrões, significados e possíveis melhorias na escrita. Através de um script personalizado, as sentenças são enviadas para a IA, que retorna análises detalhadas incluindo correção gramatical, sugestões de melhoria, identificação de emoções e avaliação da tonalidade dos textos.

## Processo

O fluxo de trabalho do projeto pode ser dividido em três etapas principais:

1. **Preparação das Sentenças:**  
   Selecionamos uma variedade de textos para que a IA possa avaliar diferentes contextos, tons e estruturas gramaticais.

2. **Envio e Processamento das Sentenças:**  
   Utilizamos a API da IA para enviar cada sentença e receber respostas que englobam:
   - Correção gramatical
   - Sugestões de melhoria
   - Identificação das emoções presentes
   - Avaliação da tonalidade e clareza

3. **Registro e Análise dos Resultados:**  
   Todas as respostas da IA são documentadas, permitindo uma análise comparativa e a identificação de pontos que podem ser aprimorados.

## Prints de Tela

### 1. Configuração do Recurso no Azure

Nesta etapa, o ambiente é configurado no Azure para viabilizar a análise das sentenças. A interface mostra como configurar itens essenciais, como:

- **Subscription e Resource Group:**  
  Escolha ou criação do grupo de recursos.

- **Instance Details:**  
  Seleção da região, definição do nome (campo obrigatório) e do tier de preços, com mensagens de alerta para campos não preenchidos.

- **Informações Adicionais:**  
  Links para detalhes sobre preços e avisos relacionados à utilização responsável dos serviços de IA.

![Configuração do Recurso de Linguagem no Azure](./prints/jdhNpxRfNtrs5Cb24o5je.png)

---

### 2. Experimentação com Análise de Sentimentos e Opiniões

A interface do Azure AI Language Studio é utilizada para testar a análise de sentimentos. As funcionalidades incluem:

- **Seleção de Idioma:**  
  Escolha do idioma adequado para o texto.

- **Seleção do Recurso Azure:**  
  Definição do ambiente configurado para processar a análise.

- **Campo de Entrada de Texto:**  
  Área para inserir o texto a ser analisado. No exemplo, é exibida uma resenha de um hotel:


![Interface de Análise de Sentimentos no Azure AI Language Studio](./prints/Mdgd7iwFG6uBUZfLtdPhQ.png)

---

### 3. Detalhamento dos Resultados da Análise de Sentimentos

Após o processamento, o sistema apresenta uma análise detalhada da resenha com os seguintes insights:

- **Distribuição do Sentimento:**  
- 96,00% negativo  
- 3,00% neutro  
- 0,00% positivo  
Essa distribuição evidencia uma experiência predominantemente insatisfatória.

- **Destaque de Palavras e Frases-Chave:**  
Frases impactantes, como *"Tired hotel with poor service"*, e termos relevantes como *"hotel"* e *"service"* são identificados e destacados.

- **Insights Adicionais:**  
Informações sobre a idade do estabelecimento e a necessidade de atualização dos móveis, sugerindo áreas de melhoria.

![Resultados da Análise de Sentimentos](./prints/BW1jMoyLD9Ujjo774XPrm.png)

---

### 4. Integração com o Serviço de Bot do Azure

O diagrama a seguir demonstra como o **Serviço de Bot do Azure** integra diversas interfaces (web, e-mail, chat) para interagir com um bot conectado a um serviço de IA. Essa integração:

- **Multicanais de Comunicação:**  
Permite que diferentes interfaces interajam com o bot proporcionando respostas automatizadas e eficientes.

- **Otimização do Atendimento:**  
Centraliza o gerenciamento das interações e agiliza as respostas.

- **Fonte e Credibilidade:**  
Destaca a integração como parte da robusta plataforma Microsoft, reforçando a confiabilidade do serviço.

![Serviço de Bot do Azure](./prints/mzz5xcRqWp8fv3vSkVGDD.png)

---

## Conclusão

Este projeto demonstra como a Inteligência Artificial pode ser aplicada para realizar análises textuais detalhadas, identificando pontos críticos e oportunidades de melhoria em diversos contextos. A integração com serviços como o Azure Bot Service amplifica a capacidade de resposta automatizada e centralizada, proporcionando uma experiência de usuário mais robusta e eficiente.

Explore novas funcionalidades e adaptações para enriquecer ainda mais os insights obtidos e transformar a forma como os textos são avaliados e aprimorados!

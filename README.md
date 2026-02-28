# 💸 App de Finanças Pessoais do Genesis1309 com Vibe Coding

PRD refinado no Grok

# PRD - Aplicativo de Organização de Finanças Pessoais por Conversa

## Contexto
Quero criar um aplicativo de Organização de Finanças Pessoais que funcione por meio de conversas em linguagem natural.  
A ideia é facilitar o controle financeiro de forma simples e natural, sem a necessidade de formulários manuais ou planilhas complexas.  
Imagine poder registrar um gasto apenas dizendo "Gastei R$50 no almoço hoje" e o app entender tudo automaticamente!

## Problema
Muitas pessoas desistem de controlar seus gastos porque os aplicativos atuais exigem muita entrada manual de dados e oferecem pouca personalização.  
Isso torna o processo cansativo e pouco motivador.  
O app resolve isso com uma experiência conversacional intuitiva, classificações automáticas de transações e recomendações personalizadas de economia.

## Público-Alvo
Pessoas que querem começar a organizar suas finanças de forma prática e sem complicações, especialmente iniciantes.  
Exemplos: jovens adultos, estudantes ou profissionais que nunca usaram ferramentas financeiras avançadas, mas buscam uma introdução amigável.

## Funcionalidades-Chave
1. Registrar gastos via chat em linguagem natural  
2. Classificar automaticamente as transações (ex.: comida, transporte, lazer)  
3. Definir e acompanhar metas financeiras (ex.: "Economizar R$500 por mês")  
4. Receber dicas de economia do “Agente Financeiro” (ex.: sugestões personalizadas)  
5. Visualizar relatórios simples e personalizados com gráficos fáceis de entender  
   - Gráficos de pizza para categorias  
   - Linhas para evolução mensal  
   - Resumo textual claro e motivador

## Plano de MVP (Minimum Viable Product)

### Principais Telas do MVP
1. Tela de Boas-Vindas / Onboarding  
   - Chat inicial explicando o app  
   - Exemplo: “Olá! Sou seu Agente Financeiro. Vamos organizar suas finanças conversando?”  
   - Dicas rápidas de uso

2. Tela de Chat Principal  
   - Interface estilo mensageiro  
   - Input em linguagem natural  
   - Confirmações do app (ex.: “Entendi! Gasto de R$20 em Alimentação adicionado”)  
   - Botões rápidos para ações comuns

3. Tela de Relatórios  
   - Gráficos simples (pizza, barras, linha)  
   - Resumo textual  
   - Exemplo: “Você gastou 40% em comida este mês – que tal uma dica para economizar?”

4. Tela de Metas  
   - Lista de metas ativas  
   - Barra de progresso  
   - Opção de editar/adicionar via chat

Total estimado: 4 telas principais

### Recursos Necessários
- Frontend: React Native ou Flutter (mobile)  
- Backend: Node.js ou Python (Flask/FastAPI)  
- Processamento de linguagem natural: NLTK, spaCy ou Dialogflow  
- Classificação automática: modelo simples (scikit-learn ou regras + palavras-chave)  
- Banco de dados: SQLite ou Firebase (inicialmente local/offline)  
- Gráficos: Chart.js (web/mobile) ou similar  
- Notificações: Firebase Cloud Messaging (opcional no MVP)

### Esboço de Validação Inicial
1. Testes internos: registrar gastos variados, criar metas, verificar classificação (~80% acerto)  
2. Feedback com 5–10 usuários iniciantes (1 semana de uso)  
   - Perguntas: Foi fácil? As dicas ajudaram? Nota de 1–10  
3. Métricas principais:  
   - Quantos gastos registrados via chat  
   - Taxa de retorno (retenção)  
   - Satisfação geral  
4. Iteração rápida com base no feedback

Foco do MVP: validar a experiência conversacional + simplicidade + motivação para continuar usando.


- Seu **prompt final** (PRD);  
Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document):
- Prints ou pequenos vídeos das interações com a IA; 
<img width="1313" height="839" alt="image" src="https://github.com/user-attachments/assets/ad5eecb8-161d-4c08-b9c3-42b89d53b189" />

- Um resumo do que o seu **App de Finanças Pessoais** faz;
Um controle completo de todos os tipos de gastos e com suporte de um agente financeiro por I.A
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  No Lovable não precisei gastar nenhum credito e saiu perfeito o APP
  - O que não funcionou como o esperado?  
  Saiu como esperado, não tive problemas
  - O que aprendeu sobre conversar com IAs?
  Facilita demais no dia dia, o Vibe coding veio para proporcionar facilidade e agilidade.

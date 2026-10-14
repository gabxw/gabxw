<h1 align="center">Gabriel Maciel</h1>

<p align="center">
  Desenvolvedor backend em Belo Horizonte. Construo sistemas internos, automações e integrações,<br>
  e no tempo livre construo coisas para entender como elas quebram.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gabriel-maciel-625980268">
    <img src="https://img.shields.io/badge/LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=4ADE80" alt="LinkedIn">
  </a>
  <a href="mailto:gabriel.jmaciel13@gmail.com">
    <img src="https://img.shields.io/badge/Email-161B22?style=for-the-badge&logo=gmail&logoColor=4ADE80" alt="Email">
  </a>
</p>

---

## No trabalho

Sou desenvolvedor no **Grupo Roma Brasil**, rede de concessionárias. Cuido de sistemas que a operação usa todo dia:

- um hub interno em Laravel e SQL Server com rotinas de financeiro, fechamento contábil, logística e comercial;
- uma conciliação entre a margem apurada no Power BI e o gerencial contábil, com IA explicando de onde vem cada diferença;
- automações em Python e rotinas agendadas que geram títulos, enviam relatórios e avisam prazos.

Boa parte do trabalho é entender a regra de negócio direito antes de escrever código. É a parte de que eu mais gosto.

---

## Projetos

### [FlowForge](https://github.com/gabxw/flowforge)

<img src="https://raw.githubusercontent.com/gabxw/flowforge/main/docs/screenshots/percurso.gif" alt="Workflow publicado, evento recebido por webhook e caminho percorrido pela execução">

Motor de automação por workflows, no estilo n8n. Você desenha o fluxo, publica, e cada evento recebido por webhook vira uma execução processada por um Worker.

Chamar uma API é fácil. Difícil é ser confiável quando algo falha no meio: a fila cai depois do banco confirmar, o Worker morre depois de um POST, o mesmo evento chega duas vezes. O FlowForge trata cada um desses casos de forma explícita, com outbox transacional, chave de idempotência, fencing token, checkpoints e retry só no que é seguro repetir, e cada caso tem teste com PostgreSQL e RabbitMQ de verdade.

`.NET 10` `PostgreSQL` `RabbitMQ` `React` `React Flow` `OpenTelemetry`

### [Conta Aberta](https://github.com/gabxw/conta-aberta)

Nasceu no hackathon Ruptura 2026, no case de carro por assinatura. Mostra ao cliente o que a mensalidade cobre e quanto ele gastaria tendo o carro próprio. Tem um assistente de IA com tool use: o número vem da regra de negócio, a explicação vem do modelo.

`.NET 10` `Next.js` `PostgreSQL` `Claude / OpenAI`

### [ZapBebidas](https://zapbebidas.com)

SaaS de cardápio digital e pedidos para distribuidoras de bebidas, feito para várias lojas, com pagamento pelo Mercado Pago e atendimento pelo WhatsApp.

### Outros

- **[AgendeCorte](https://agendecorte.com)**: agendamento online para barbearias, com painel e avisos pelo WhatsApp.
- **[GásFácil](https://github.com/gabxw/gasfacil)**: operação de distribuidora de gás, com pedidos, estoque e WhatsApp.
- **[VÉRTICE Hub](https://github.com/gabxw/vertice-hub)**: e-commerce completo, do catálogo ao checkout com Mercado Pago e PayPal.

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=dotnet,cs,laravel,php,python,postgres,rabbitmq,docker,react,ts&perline=10" alt="Stack">
</p>

Backend em **C#/.NET** e **Laravel**, automação em **Python**, dados em **PostgreSQL** e **SQL Server**. No front, React com TypeScript quando o projeto pede.

---

## Trajetória

**Grupo Roma Brasil**: desenvolvedor de software. Sistemas internos, integrações e automação.<br>
**SPM Infor**: help desk e suporte de TI.

Engenharia de Software (UFBRA) · Técnico em Desenvolvimento de Sistemas (SENAI CTTI)

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gabxw/gabxw/output/github-contribution-grid-snake-dark.svg">
  <img alt="Cobrinha comendo o gráfico de contribuições" src="https://raw.githubusercontent.com/gabxw/gabxw/output/github-contribution-grid-snake.svg">
</picture>

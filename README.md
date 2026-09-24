# Lucas Lorenço

**Desenvolvedor full-stack & IA · construo o sistema inteiro, do hardware ao agente.**
Serra Gaúcha, RS · disponível para PJ e vagas Full Stack / IA

[Portfólio](https://https://claude.ai/artifact/PANp9wCJ6oT7ZCBBZSzhNJ) · [LinkedIn](https://linkedin.com/in/lucaslorenco) · lucasfgl2003@gmail.com

---

## O que eu faço

Pego uma ideia e levo até o que roda em produção: back-end, front-end, banco, infra, pagamento, IA. Co-fundei uma empresa de tecnologia e, com meu sócio, construí as entranhas dela — não um produto, a companhia inteira. Hoje meu dia a dia é C# / .NET, Next.js / TypeScript, PostgreSQL, Docker e agentes com Claude Code.

---

## Projetos

### ScaleTAP — co-fundador · plataforma em produção
Empresa de tecnologia: cartões e moedas NFC que levam o cliente direto à avaliação no Google, com hub de gestão, loja e perfil público. *(código privado — arquitetura abaixo)*

**Arquitetura**
- **API** em **C# / .NET 10** — ASP.NET Core com Controllers, **Dapper** (SQL na mão, sem ORM pesado), CSharpFunctionalExtensions, Serilog
- **Banco**: **PostgreSQL 17** em container, schema versionado por arquivo (não por migrations de framework)
- **Front**: três aplicações separadas em **Next.js 16 / React 19 / TypeScript / Tailwind 4** — hub do cliente e admin · site de vendas e loja · perfil público `/@handle`
- **Pagamento**: **Stripe** — checkout hospedado, assinaturas no Customer Portal, BRL
- **Serviços**: e-mail transacional via Resend; storage de imagens no próprio servidor
- **Infra**: tudo em **Docker** numa VM Linux, atrás de **Cloudflare Tunnel**
- **CI**: **GitLab**, runner na própria VM, um pipeline por repositório

**Além do código**: produto físico NFC (hardware + IoT), pipeline de imagem com IA, marca, presença digital e tráfego.

### Genus — agente pessoal local · open source
Um agente que roda 100% na minha máquina: memória em Markdown versionada em Git, orquestração com **Claude Code** em modo headless, servidor **Python** sem dependências, interface de voz com um **orbe em WebGL (GLSL)** que pulsa por palavra, **transcrição local com Whisper**, anexos de imagem e PDF, e um "conselho" de agentes que discordam entre si antes de concluir.

- **Motor trocável**: uma única peça fala com a IA (hoje `claude -p`; amanhã a API) — desenhado para virar produto
- **Camadas**: memória (prosa) separada de registro (CSV) — o que é conhecimento vs. o que é contável
- **Privacidade por padrão**: áudio nunca sai da máquina; escrita do agente restrita a pastas específicas
- Repo: `github.com/lucaslorenco/genus` *(a publicar)*

### SEPA · OSMEA — estratégia digital & infraestrutura para negócios locais
Implantação de presença digital do zero pelo meu próprio playbook: Google Business, coleta de avaliações, medição (GA4, Search Console, Meta Pixel), aquisição paga, site. Contratos ativos.

---

## Stack

| | |
|---|---|
| **Back-end** | C# · .NET 10 · ASP.NET Core · Dapper · Serilog · APIs REST · webhooks |
| **Front-end** | Next.js 16 · React 19 · TypeScript · Tailwind 4 · CSS · HTML · WebGL / GLSL |
| **Dados** | PostgreSQL 17 · SQL · analytics (GA4, Search Console, Meta) |
| **Infra** | Docker · Linux · Cloudflare Tunnel · GitLab CI · Git |
| **IA & automação** | Claude Code (agentes, hooks, skills) · Python · Whisper · integração de APIs (Stripe, Resend, Meta Graph) · Bash |
| **Produto** | IoT / NFC · Stripe (checkout, assinaturas) · design de marca · vídeo (direção, captação, luz, edição) |

---

## Como eu trabalho

- **De ponta a ponta.** Não entrego "a parte do front" — entrego a coisa funcionando, do banco ao botão.
- **IA no fluxo, não como enfeite.** Agentes que registram, consultam e decidem, com regras de escrita e fonte obrigatória.
- **Decisão por dado.** Número vem de consulta, nunca de estimativa.
- **Enfeite não pode derrubar ferramenta.** Falha silenciosa e limpa antes de risco à base.

---

📫 lucasfgl2003@gmail.com · [LinkedIn](https://linkedin.com/in/lucaslorenco)

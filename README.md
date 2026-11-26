# Painel de implementação comercial · 90 dias

Painel ágil (fases, sprints, quadro, métricas e anotações) com acesso por login.

- Página estática hospedada no GitHub Pages (`index.html`).
- Login e dados no Supabase. O conteúdo do plano fica só no banco, protegido por regras de acesso (RLS): somente e-mails autorizados leem e editam.
- A chave que aparece no código é a *publishable key* do Supabase, feita para ficar em páginas públicas.

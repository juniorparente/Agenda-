# Rotina — Planejamento Pessoal

Planejamento pessoal: calendário, semana, tarefas, hábitos e metas de questões. Página única em HTML, sem dependências externas.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `rotina`).
2. Envie os arquivos desta pasta (`index.html`, `README.md`, `.nojekyll`) em **Add file → Upload files**.
3. Vá em **Settings → Pages**, em *Source* escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
4. Em ~1 minuto o app fica em `https://SEU-USUARIO.github.io/rotina/`.

## Seus dados

- Tudo fica salvo no **localStorage do navegador** (chave `rotina:v1`). Nada é enviado ao GitHub.
- O endereço github.io tem armazenamento separado do arquivo aberto no computador. Para levar seus dados:
  1. No arquivo antigo, abra **Dados e backup → Baixar backup**.
  2. No app publicado, use **Restaurar** e escolha o arquivo `rotina-backup-AAAA-MM-DD.json`.
- Use o mesmo processo para passar de um aparelho para outro.

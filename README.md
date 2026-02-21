# Exame do Estado Mental (EEM) — gerador em HTML

Gerador simples, estático e pronto para **GitHub Pages**, para montar o **Exame do Estado Mental** por seleções e observações curtas, e ao final gerar um **modelo integrado** com botão de **copiar**.

## Como publicar no GitHub Pages

1. Crie um repositório (ex.: `eem`).
2. Faça upload deste projeto (ou envie via git).
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` / **Folder**: `/ (root)`
5. Salve. O GitHub informará a URL do site.

## Como usar

- Preencha as seleções e, se quiser, adicione observações curtas em cada seção.
- Clique em **Gerar e copiar automaticamente**.
- O texto final aparece em **Modelo Final Integrado** e já vai para a área de transferência.

## Estrutura

- `index.html` — site (HTML/CSS/JS) em arquivo único, sem dependências.
- `.nojekyll` — evita processamento do Jekyll (opcional, mas recomendado).

## Observação

Criado por Rodrigo Carneiro. Uso exclusivo para fins educacionais. 2026.

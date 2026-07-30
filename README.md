# CT Forte Jarinu — Site

Site institucional do **Centro de Treinamento Forte** (Jarinu/SP) — Muay Thai e Jiu-Jitsu.

## Páginas

- `index.html` — Página principal (home)
- `muay-thai.html` — Página da modalidade Muay Thai
- `jiu-jitsu.html` — Página da modalidade Jiu-Jitsu

Os arquivos são **autossuficientes**: logos, texturas e estilos estão embutidos (base64/CSS inline). Não há dependências externas além das fontes do Google Fonts (carregadas via CDN). Basta manter os três arquivos na mesma pasta.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `ctforte-site`).
2. Envie estes arquivos para o repositório (veja os comandos abaixo).
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, selecione a branch `main` e a pasta `/ (root)`.
5. Salve. Em alguns minutos o site fica disponível em:
   `https://SEU-USUARIO.github.io/ctforte-site/`

## Subir via linha de comando

```bash
git init
git add .
git commit -m "Site CT Forte Jarinu"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/ctforte-site.git
git push -u origin main
```

> Troque `SEU-USUARIO` pelo seu usuário do GitHub.

## Subir sem linha de comando

1. No GitHub, abra o repositório novo.
2. Clique em **Add file → Upload files**.
3. Arraste `index.html`, `muay-thai.html` e `jiu-jitsu.html`.
4. Clique em **Commit changes**.
5. Ative o **GitHub Pages** em Settings → Pages (branch `main`, pasta root).

## Pendências (placeholders a substituir)

- **Foto do professor** Renaldo Bueno — hoje é uma silhueta ilustrativa.
- **Valores e planos** das aulas — cards de "Aula experimental" ainda sem preços.
- Confirmar o número de **WhatsApp** usado nos botões: (11) 99850-0816.

## Contato da academia

- Endereço: R. José de Moura, 50 - Centro, Jarinu - SP, 13240-000
- Telefone/WhatsApp: (11) 99850-0816
- Instagram: https://www.instagram.com/ct_forte/
- Facebook: https://www.facebook.com/ctfortemma/

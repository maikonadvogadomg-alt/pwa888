# 🧬 Receita para recriar: Maikon Caldeira — Aplicativos

_Gerada sem IA, lendo 54 arquivo(s). Serve para remontar este app como HTML modular — com qualquer IA, um arquivo por vez._

## 1. O que é

- **Nome:** Maikon Caldeira — Aplicativos
- **Partes de código:** 28 (28 tela, 0 logica, 0 servidor, 0 dados, 0 estilo)
- **Tem servidor (rotas /api):** não — dá para ser só HTML
- **Peças de fora (bibliotecas):**  + JSON.stringify(principal) + ,  + q + u + q + , crypto, electron, fs, http, os, path, react, react-dom, url, x

## 2. Estrutura modular proposta

```
index.html            ← a página; chama os módulos NA ORDEM
css/app.css           ← o visual
js/00-core.js         ← a "locomotiva": cria window.APP (registrar, guardar, avisar)
js/10-1.js            ← Mini SK — 🔗 Meus Links (era 1.html)
js/15-10.js           ← Mini SK 2 — 🔗 Meus Links (era 10.html)
js/20-11.js           ← Preparador Universal — 🧰 Preparador Universal (era 11.html)
js/25-12.js           ← Backup para o HD (era 12.html)
js/30-13.js           ← Celular e PC Livres — O que aconteceu com o seu celular (era 13.html)
js/35-14.js           ← Comparador de Versões — ⚖️ Comparador de Versões (era 14.html)
js/40-15.js           ← Colador de Links — 🔗 Colador de Links (era 15.html)
js/45-16.js           ← Catalogador de Códigos — 🗂️ Catalogador de Códigos (era 16.html)
js/50-17.js           ← Colecionador de Comandos (era 17.html)
js/55-18.js           ← Laboratório HTML — Advocacia Previdenciária (era 18.html)
js/60-19.js           ← Numerador de Códigos — 🔢 Numerador de Códigos (era 19.html)
js/65-20.js           ← 🧹 Faxina de Repetidos — 🧹 Faxina de Repetidos (era 20.html)
js/70-21.js           ← Catalogador de Códigos — 🗂️ Catalogador de Códigos (era 21.html)
js/75-22.js           ← Raio-X de Pacotes — 🩻 Raio-X de Pacotes (era 22.html)
js/80-23.js           ← Arrumador de Backups — 🗃 Arrumador de Backups (era 23.html)
js/85-24.js           ← Raio-X de Pacotes — 🩻 Raio-X de Pacotes (era 24.html)
js/90-25.js           ← Colador de Links — 🔗 Colador de Links (era 25.html)
js/91-26.js           ← Comparação Mini SK — ⚖️ Mini SK 17/10 × v20/10-D (era 26.html)
js/92-27.js           ← Meus Links — 🔗 Meus Links (era 27.html)
js/93-3.js            ← Mini SK 2 — 🔗 Meus Links (era 3.html)
js/94-4.js            ← Picotador de Memória e Backup — ✂️ Picotador de Memória e Backup (era 4.html)
js/95-5.js            ← ProjetoLens — Analisador de Projetos — ProjetoLens (era 5.html)
js/96-6.js            ← Montador Universal — 🧩 Montador Universal (era 6.html)
js/97-7.js            ← Mini SK 2 — 🔗 Meus Links (era 7.html)
js/98-8.js            ← Laboratório — 🔬 Laboratório (era 8.html)
js/98-9.js            ← Mini SK 2 — 🔗 Meus Links (era 9.html)
js/98-hub.js          ← pwa888 — pwa888 (era hub.html)
js/98-inicio.js       ← Maikon Caldeira — Aplicativos — MAIKON CALDEIRA (era index.html)
js/99-app.js          ← o último: monta a tela com o que embarcou
```

## 3. As partes, uma por uma

| # | Era | Vira | Tipo | O que faz | Usa |
|---|---|---|---|---|---|
| 1 | `1.html` | `js/10-1.js` | tela | Mini SK — 🔗 Meus Links | manifest.json, favicon.ico, icon.svg, apple-touch-icon.png |
| 2 | `10.html` | `js/15-10.js` | tela | Mini SK 2 — 🔗 Meus Links | Mini-SK-2.webmanifest, favicon.ico, icon.svg, apple-touch-icon.png |
| 3 | `11.html` | `js/20-11.js` | tela | Preparador Universal — 🧰 Preparador Universal | package.json |
| 4 | `12.html` | `js/25-12.js` | tela | Backup para o HD | — |
| 5 | `13.html` | `js/30-13.js` | tela | Celular e PC Livres — O que aconteceu com o seu celular | — |
| 6 | `14.html` | `js/35-14.js` | tela | Comparador de Versões — ⚖️ Comparador de Versões | — |
| 7 | `15.html` | `js/40-15.js` | tela | Colador de Links — 🔗 Colador de Links | — |
| 8 | `16.html` | `js/45-16.js` | tela | Catalogador de Códigos — 🗂️ Catalogador de Códigos | — |
| 9 | `17.html` | `js/50-17.js` | tela | Colecionador de Comandos | — |
| 10 | `18.html` | `js/55-18.js` | tela | Laboratório HTML — Advocacia Previdenciária | — |
| 11 | `19.html` | `js/60-19.js` | tela | Numerador de Códigos — 🔢 Numerador de Códigos | — |
| 12 | `20.html` | `js/65-20.js` | tela | 🧹 Faxina de Repetidos — 🧹 Faxina de Repetidos | — |
| 13 | `21.html` | `js/70-21.js` | tela | Catalogador de Códigos — 🗂️ Catalogador de Códigos | — |
| 14 | `22.html` | `js/75-22.js` | tela | Raio-X de Pacotes — 🩻 Raio-X de Pacotes | — |
| 15 | `23.html` | `js/80-23.js` | tela | Arrumador de Backups — 🗃 Arrumador de Backups | — |
| 16 | `24.html` | `js/85-24.js` | tela | Raio-X de Pacotes — 🩻 Raio-X de Pacotes | — |
| 17 | `25.html` | `js/90-25.js` | tela | Colador de Links — 🔗 Colador de Links | — |
| 18 | `26.html` | `js/91-26.js` | tela | Comparação Mini SK — ⚖️ Mini SK 17/10 × v20/10-D | — |
| 19 | `27.html` | `js/92-27.js` | tela | Meus Links — 🔗 Meus Links | — |
| 20 | `3.html` | `js/93-3.js` | tela | Mini SK 2 — 🔗 Meus Links | Mini-SK-2.webmanifest, favicon.ico, icon.svg, apple-touch-icon.png |
| 21 | `4.html` | `js/94-4.js` | tela | Picotador de Memória e Backup — ✂️ Picotador de Memória e Backup | — |
| 22 | `5.html` | `js/95-5.js` | tela | ProjetoLens — Analisador de Projetos — ProjetoLens | ${url},  |
| 23 | `6.html` | `js/96-6.js` | tela | Montador Universal — 🧩 Montador Universal | — |
| 24 | `7.html` | `js/97-7.js` | tela | Mini SK 2 — 🔗 Meus Links | manifest.json, favicon.ico, icon.svg, apple-touch-icon.png |
| 25 | `8.html` | `js/98-8.js` | tela | Laboratório — 🔬 Laboratório | — |
| 26 | `9.html` | `js/98-9.js` | tela | Mini SK 2 — 🔗 Meus Links | manifest.json, favicon.ico, icon.svg, apple-touch-icon.png |
| 27 | `hub.html` | `js/98-hub.js` | tela | pwa888 — pwa888 | hub.webmanifest, favicon.ico, icon.svg, apple-touch-icon.png |
| 28 | `index.html` | `js/98-inicio.js` | tela | Maikon Caldeira — Aplicativos — MAIKON CALDEIRA | manifest.json, favicon.ico, icon.svg, apple-touch-icon.png |

## 4. Montar passo a passo (cada bloco é um pedido pronto: 📋 Copiar → colar na IA)

### Passo 0 — combinar as regras com a IA

```text
Vamos recriar o app "Maikon Caldeira — Aplicativos" como HTML MODULAR, que abre pelo index.html, sem servidor e sem nada da Replit.
Regras: (1) index.html chama os arquivos js/ na ordem, antes do </body>; (2) js/00-core.js cria window.APP com APP.registrar(modulo), APP.guardar(chave, valor) em IndexedDB/localStorage e APP.avisar(texto); (3) cada arquivo js/NN-nome.js cuida de UM assunto, começa com (function (APP) { e termina com })(window.APP); (4) js/99-app.js vem por último e monta a tela com os módulos registrados; (5) textos em português do Brasil.
Vou pedir UM arquivo por vez. Responda só com o arquivo completo, sem cortar nada. Primeiro: crie index.html, css/app.css e js/00-core.js.
```

### Passo 1 — `js/10-1.js` (era `1.html`, 11646 linhas)

```text
Crie js/10-1.js. Ele faz: Mini SK — 🔗 Meus Links.
No app original ele tinha estas funções/partes: modal, done, openDB, reqP, nada, extOf, baseName, dirName, norm, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, saveNow, touch, getDir.
O original usava as bibliotecas  + q + u + q + , react, react-dom,  + JSON.stringify(principal) + , http, fs, path, os, electron, crypto, url: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: dados.json, https://api.anthropic.com/v1/models?limit=100, http://127.0.0.1:11434/api/version, https://registry.npmjs.org, https://api.npms.io/v2/search?size=15&q=, sw.js, https://api.github.com, ./, https://api.github.com/repos/, https://api.expo.dev/graphql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 2 — `js/15-10.js` (era `10.html`, 11047 linhas)

```text
Crie js/15-10.js. Ele faz: Mini SK 2 — 🔗 Meus Links.
No app original ele tinha estas funções/partes: modal, done, openDB, reqP, nada, extOf, baseName, dirName, norm, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, saveNow, touch, getDir.
O original usava as bibliotecas  + q + u + q + , react, react-dom,  + JSON.stringify(principal) + , http, fs, path, os, electron, crypto, url: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: dados.json, https://api.anthropic.com/v1/models?limit=100, http://127.0.0.1:11434/api/version, https://registry.npmjs.org, https://api.npms.io/v2/search?size=15&q=, https://api.github.com, ./, https://api.github.com/repos/, https://api.expo.dev/graphql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 3 — `js/20-11.js` (era `11.html`, 833 linhas)

```text
Crie js/20-11.js. Ele faz: Preparador Universal — 🧰 Preparador Universal.
O original usava as bibliotecas electron, path, fs, http: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 4 — `js/25-12.js` (era `12.html`, 284 linhas)

```text
Crie js/25-12.js. Ele faz: Backup para o HD.
No app original ele tinha estas funções/partes: humano, log, paresTodos, parGuardar, parApagar, permissao, pintarEscolhas, escolher, listar, lerRegistro, gravarRegistro, existeNoDestino, calcular, copiarUm, executar, olhar, mesmaPasta, pintarPares.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 5 — `js/30-13.js` (era `13.html`, 365 linhas)

```text
Crie js/30-13.js. Ele faz: Celular e PC Livres — O que aconteceu com o seu celular.
No app original ele tinha estas funções/partes: abrir.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 6 — `js/35-14.js` (era `14.html`, 389 linhas)

```text
Crie js/35-14.js. Ele faz: Comparador de Versões — ⚖️ Comparador de Versões.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 7 — `js/40-15.js` (era `15.html`, 686 linhas)

```text
Crie js/40-15.js. Ele faz: Colador de Links — 🔗 Colador de Links.
No app original ele tinha estas funções/partes: uid, ler, gravar, nomeDe, pintar, fixar, tirar, mover, recarregar, pintarJanela, iniciar, montar, salvar, daLista, contar, pintarListas, quadro, mostrar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 8 — `js/45-16.js` (era `16.html`, 303 linhas)

```text
Crie js/45-16.js. Ele faz: Catalogador de Códigos — 🗂️ Catalogador de Códigos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 9 — `js/50-17.js` (era `17.html`, 1672 linhas)

```text
Crie js/50-17.js. Ele faz: Colecionador de Comandos.
No app original ele tinha estas funções/partes: req, QR8bitByte, QRBitBuffer, QRPolynomial, QRRSBlock, QRCode, esc, semAcento, uid, toast, ler, salvar, copiar, adivinhar, desenharFiltros, desenhar, cartao, lembrete.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 10 — `js/55-18.js` (era `18.html`, 823 linhas)

```text
Crie js/55-18.js. Ele faz: Laboratório HTML — Advocacia Previdenciária.
No app original ele tinha estas funções/partes: separar, ler, cssDosAjustes, regra, completo, guardar, caminho, limpo, info, marcar, pagina, quemE, hex, transparente, num, montar, carregar, enviar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 11 — `js/60-19.js` (era `19.html`, 241 linhas)

```text
Crie js/60-19.js. Ele faz: Numerador de Códigos — 🔢 Numerador de Códigos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 12 — `js/65-20.js` (era `20.html`, 470 linhas)

```text
Crie js/65-20.js. Ele faz: 🧹 Faxina de Repetidos — 🧹 Faxina de Repetidos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 13 — `js/70-21.js` (era `21.html`, 303 linhas)

```text
Crie js/70-21.js. Ele faz: Catalogador de Códigos — 🗂️ Catalogador de Códigos.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 14 — `js/75-22.js` (era `22.html`, 206 linhas)

```text
Crie js/75-22.js. Ele faz: Raio-X de Pacotes — 🩻 Raio-X de Pacotes.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 15 — `js/80-23.js` (era `23.html`, 319 linhas)

```text
Crie js/80-23.js. Ele faz: Arrumador de Backups — 🗃 Arrumador de Backups.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 16 — `js/85-24.js` (era `24.html`, 206 linhas)

```text
Crie js/85-24.js. Ele faz: Raio-X de Pacotes — 🩻 Raio-X de Pacotes.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 17 — `js/90-25.js` (era `25.html`, 686 linhas)

```text
Crie js/90-25.js. Ele faz: Colador de Links — 🔗 Colador de Links.
No app original ele tinha estas funções/partes: uid, ler, gravar, nomeDe, pintar, fixar, tirar, mover, recarregar, pintarJanela, iniciar, montar, salvar, daLista, contar, pintarListas, quadro, mostrar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 18 — `js/91-26.js` (era `26.html`, 83 linhas)

```text
Crie js/91-26.js. Ele faz: Comparação Mini SK — ⚖️ Mini SK 17/10 × v20/10-D.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 19 — `js/92-27.js` (era `27.html`, 6 linhas)

```text
Crie js/92-27.js. Ele faz: Meus Links — 🔗 Meus Links.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 20 — `js/93-3.js` (era `3.html`, 11047 linhas)

```text
Crie js/93-3.js. Ele faz: Mini SK 2 — 🔗 Meus Links.
No app original ele tinha estas funções/partes: modal, done, openDB, reqP, nada, extOf, baseName, dirName, norm, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, saveNow, touch, getDir.
O original usava as bibliotecas  + q + u + q + , react, react-dom,  + JSON.stringify(principal) + , http, fs, path, os, electron, crypto, url: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: dados.json, https://api.anthropic.com/v1/models?limit=100, http://127.0.0.1:11434/api/version, https://registry.npmjs.org, https://api.npms.io/v2/search?size=15&q=, https://api.github.com, ./, https://api.github.com/repos/, https://api.expo.dev/graphql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 21 — `js/94-4.js` (era `4.html`, 458 linhas)

```text
Crie js/94-4.js. Ele faz: Picotador de Memória e Backup — ✂️ Picotador de Memória e Backup.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 22 — `js/95-5.js` (era `5.html`, 11933 linhas)

```text
Crie js/95-5.js. Ele faz: ProjetoLens — Analisador de Projetos — ProjetoLens.
O original usava as bibliotecas x: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: https://registry.npmjs.org/${dep.name}/latest, https://registry.npmjs.org/${name}/latest. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 23 — `js/96-6.js` (era `6.html`, 952 linhas)

```text
Crie js/96-6.js. Ele faz: Montador Universal — 🧩 Montador Universal.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 24 — `js/97-7.js` (era `7.html`, 11600 linhas)

```text
Crie js/97-7.js. Ele faz: Mini SK 2 — 🔗 Meus Links.
No app original ele tinha estas funções/partes: modal, done, openDB, reqP, nada, extOf, baseName, dirName, norm, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, saveNow, touch, getDir.
O original usava as bibliotecas  + q + u + q + , react, react-dom,  + JSON.stringify(principal) + , http, fs, path, os, electron, crypto, url: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: dados.json, https://api.anthropic.com/v1/models?limit=100, http://127.0.0.1:11434/api/version, https://registry.npmjs.org, https://api.npms.io/v2/search?size=15&q=, https://api.github.com, ./, https://api.github.com/repos/, https://api.expo.dev/graphql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 25 — `js/98-8.js` (era `8.html`, 730 linhas)

```text
Crie js/98-8.js. Ele faz: Laboratório — 🔬 Laboratório.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 26 — `js/98-9.js` (era `9.html`, 11104 linhas)

```text
Crie js/98-9.js. Ele faz: Mini SK 2 — 🔗 Meus Links.
No app original ele tinha estas funções/partes: modal, done, openDB, reqP, nada, extOf, baseName, dirName, norm, typeOf, decodeBytes, looksBinary, toBase64, fromBase64, recordFromBytes, saveNow, touch, getDir.
O original usava as bibliotecas  + q + u + q + , react, react-dom,  + JSON.stringify(principal) + , http, fs, path, os, electron, crypto, url: em HTML puro, use a versão de CDN (ou faça sem ela, se for simples).
Ele chamava estes endereços: dados.json, https://api.anthropic.com/v1/models?limit=100, http://127.0.0.1:11434/api/version, https://registry.npmjs.org, https://api.npms.io/v2/search?size=15&q=, https://api.github.com, ./, https://api.github.com/repos/, https://api.expo.dev/graphql. Em HTML, ligue cada um à função equivalente do módulo certo.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 27 — `js/98-hub.js` (era `hub.html`, 81 linhas)

```text
Crie js/98-hub.js. Ele faz: pwa888 — pwa888.
No app original ele tinha estas funções/partes: rec, esc, card, show.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 28 — `js/98-inicio.js` (era `index.html`, 148 linhas)

```text
Crie js/98-inicio.js. Ele faz: Maikon Caldeira — Aplicativos — MAIKON CALDEIRA.
No app original ele tinha estas funções/partes: lerInfo, procurar, pintar, abrir, fechar.
Registre com APP.registrar({ nome, icone, abrir }). Devolva só o arquivo completo.
```

### Passo 29 — `js/99-app.js` e conferir

```text
Crie js/99-app.js: ele olha APP.modulos e monta o menu/abas com um botão para cada módulo. Depois, me mande o index.html atualizado com todos os <script src="js/…"> na ordem certa: js/00-core.js, js/10-1.js, js/15-10.js, js/20-11.js, js/25-12.js, js/30-13.js, js/35-14.js, js/40-15.js, js/45-16.js, js/50-17.js, js/55-18.js, js/60-19.js, js/65-20.js, js/70-21.js, js/75-22.js, js/80-23.js, js/85-24.js, js/90-25.js, js/91-26.js, js/92-27.js, js/93-3.js, js/94-4.js, js/95-5.js, js/96-6.js, js/97-7.js, js/98-8.js, js/98-9.js, js/98-hub.js, js/98-inicio.js, js/99-app.js.
```

## 5. Conferir no final

- [ ] Abrir o index.html na prévia: aparece a tela sem erro (▤ console vazio)?
- [ ] Cada botão abre a sua parte?
- [ ] Fechar e abrir de novo: os dados continuam?
- [ ] Nada com "replit", "REPL_", "@workspace" no código (🏗️ Preparar confere).
- [ ] 📱 PWA → deixar instalável; 📦 APK ou 🖥️ .exe.

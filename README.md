# QG DA LARA · widgets

Coleção de widgets para o Notion. Cada widget é uma página HTML independente, publicada de graça no **GitHub Pages** e colada no Notion com `/embed`.

| Widget | Pasta | Status |
|---|---|---|
| Calendário mensal | `calendario/` | ✅ pronto |
| Relógio e data | `relogio/` | em breve |
| Contador regressivo | `contador/` | em breve |
| Clima | `clima/` | em breve |
| Frases | `frases/` | em breve |

Link do calendário: https://larabarros70-beep.github.io/qg-widgets/calendario/

## Colocar no Notion

1. No Notion, digite `/embed` e aperte Enter.
2. Cole o link do widget → **Embed link**.
3. Arraste as bordas do bloco para ajustar o tamanho.

## Personalizar

Passe o mouse no calendário e clique no **lápis** (canto inferior direito):

- **cor:** rosa, lavanda, verde, laranja, vermelho, azul, limão
- **papel:** creme, rosa, branco
- **desenho:** flor, estrela, coração, nenhum
- **semana começa:** domingo ou segunda
- **texto na fita:** escreva o que quiser (até 24 letras)

Depois clique em **copiar link** e, no Notion, troque o link do embed: clique nos `⋯` do bloco → **Replace** / **Substituir** → cole o link novo.

> Por que pelo link? Dentro do Notion, o navegador não deixa o widget guardar preferências de forma confiável (principalmente no iPhone). Guardando tudo no link, o widget fica idêntico em todos os seus aparelhos.

### Parâmetros do link

| Parâmetro | Valores | Exemplo |
|---|---|---|
| `tema` | `rosa` · `lavanda` · `verde` · `laranja` · `vermelho` · `azul` · `limao` | `?tema=lavanda` |
| `papel` | `creme` · `rosa` · `branco` | `&papel=rosa` |
| `deco` | `flor` · `estrela` · `coracao` · `nenhum` | `&deco=estrela` |
| `inicio` | `dom` · `seg` | `&inicio=seg` |
| `titulo` | texto da fita | `&titulo=QG%20DA%20LARA` |
| `cor` | cor principal em hexadecimal, sem `#` | `&cor=E5004F` |
| `fundo` | `transparente` · `papel` | `&fundo=papel` |
| `limpo` | `1` esconde o lápis | `&limpo=1` |

## Se algo não funcionar

- **O embed fica em branco:** confira se o link abre normalmente no navegador. Se abrir, apague o bloco e faça o `/embed` de novo.
- **Quero mudar o código:** edite o `calendario/index.html` direto no GitHub (ícone de lápis) → **Commit changes**. O Notion mostra a versão nova em 1 a 2 minutos (recarregue a página).

## Dependências

- **Nenhuma API.** Data e hora vêm do próprio aparelho.
- **Fontes:** Fraunces e Caveat, do Google Fonts (gratuitas). Se não carregarem, o widget usa fontes do sistema e continua funcionando.

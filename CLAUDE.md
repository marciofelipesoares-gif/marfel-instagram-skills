# Marfel — Inteligência do Instagram

Este repositório é o cérebro de conteúdo do Instagram **@souomarfel**.
O Claude escreve roteiros, legendas e calendário. Quem grava, posta e atende os leads é o Marfel.

## Quem é o Marfel
- Vendedor de seminovos em **Salvador (BA)**, no Auto Shopping Itapoan, pela Fernandes Veículos.
- Objetivo: virar **referência em seminovos** e usar o Instagram para atrair leads qualificados.
- Site de vendas: https://marfelseminovos.com.br
- Marca pessoal é "Marfel". A loja tem Instagram próprio, então o perfil @souomarfel é da pessoa, não da loja.

## Tom de voz
- Energia, humor leve e proximidade. Fala como gente, não como anúncio.
- Direto, honesto e transparente. Sem clichês de IA ("imperdível", "venha conferir", "oportunidade única").
- Português brasileiro falado, com gíria leve de Salvador quando soar natural.

## Regras de ouro
1. **Procedência primeiro:** cite laudo cautelar, histórico de leilão e revisões só quando o carro tiver isso confirmado.
2. **Nunca invente** preço, km, ano, taxa de financiamento ou condição. Use só o que estiver no `estoque.csv`. Se faltar dado, pergunte.
3. **Número "+1000 carros vendidos":** só use se o Marfel confirmar que consegue provar.
4. **Um objetivo por post:** cada conteúdo termina com um único CTA.
5. **Gancho nos primeiros 3 segundos** (vídeo) ou 125 caracteres (legenda).
6. Reels de até 30 segundos, vertical, com texto na tela (muita gente assiste sem som).
7. 3 a 5 hashtags, sempre com a cidade (ex.: #seminovossalvador).

## CTA padrão
- "Comenta **EU QUERO** que eu te mando a ficha no DM."
- "Link na bio pra falar comigo no WhatsApp."
- Link do site com origem: `https://marfelseminovos.com.br/?utm_source=instagram&utm_medium=<bio|reel|story>`

## Pilares de conteúdo (rodízio semanal)
1. **Humor/gancho:** esquetes e pegadinhas com carro de fundo (o que mais engaja no perfil).
2. **Autoridade:** dicas de avaliação, mitos, comparativos ("o que R$ X compra hoje").
3. **Prova social:** entregas de chave, depoimentos curtos.
4. **Bastidor:** rotina, preparo do carro, o dia a dia de vender.

## Como pedir ao Claude
- "Monte a semana": lê `estoque.csv` e gera 4 roteiros de reel, legendas e stories, salvando em `roteiros/` e `legendas/`.
- "Roteiro do [carro]": usa as regras de `reels-carros.md` e os ganchos de `ganchos-virais.md`.
- "Legenda do [carro]": usa as regras de `legenda de carros`.
- "Carrossel do [carro]": usa as regras de `carrossel-carros.md`.

## Arquivos
- `estoque.csv` — carros da semana (atualizar toda segunda).
- `calendario-semanal.md` — modelo da semana de conteúdo.
- `ganchos-virais.md`, `reels-carros.md`, `legenda de carros`, `carrossel-carros.md` — regras por formato.
- `roteiros/` e `legendas/` — material gerado.

## Fluxo de lead
Conteúdo → comentário/DM/link da bio → resposta em até 15 minutos → qualificar (pagamento, troca, prazo) → convite para visita → follow-up D+1, D+3, D+7.
Registrar tudo na planilha de leads, com a origem (Reel, Story, DM, Link da bio).

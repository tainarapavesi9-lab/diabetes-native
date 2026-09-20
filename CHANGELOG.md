# Changelog — blood-sugar-after-50 (Sugar Reset)

Registro de cada mudança na página, a hipótese por trás e o número que estava por trás da decisão. Formato: data, o que mudou, por quê, métrica pra acompanhar depois.

## 2026-09-19 — CTA cedo + copy mais forte + tabela de preço real
**Commit:** `8bb7999`

- Adicionado CTA leve logo depois do "Not guilt. Relief." (pico emocional da história), antes disso só existia 1 CTA no fim da checklist.
- CTA principal trocado de "See the Formula That Helped Me" (genérico) pra "Stop the 3:30 Crash — See What Changed for Me" (amarra na dor específica do texto).
- Adicionada tabela `.packs` com preço real de 2/3/6 frascos, confirmado direto no checkout (fasttrack37 → forsugarreset.com): $79 / $69 / $49 por frasco. Antes só tinha uma frase de texto dizendo "packages start at $49".
- **Não adicionado:** depoimentos (`.reviews` ficou sem uso) — sem review real de cliente, não inventamos, risco de FTC por endorsement falso.

**Antes da mudança:** 131 cliques no anúncio, 11 cliques no botão (8,4%), 0 venda.

## 2026-09-20 — Bloco de quebra de objeção
**Commit:** pendente (aguardando confirmação pra subir)

- Adicionado bloco "Before you talk yourself out of this" antes da seção de preço, com 4 objeções reais (já tentei outros suplementos / parece anúncio genérico / é caro / e se não funcionar), usando `.ing` (classe já existente na página).
- **Motivo:** no dia anterior, 426 de 470 cliques (91%) ficaram em deep engagement, mas só 13 clicaram no botão (2,8%). Gente lê até o fim e não age — sinal de objeção não resolvida, não de desinteresse.

**No momento da mudança:** 470 cliques no anúncio, 13 cliques no botão (2,8%), 0 venda.

## O que ainda não sabemos
- Se o funil advertorial → checkout direto (DTC) é o problema real, ou se é a página que ainda não convence o suficiente. Só dá pra saber comparando o EPC da oferta (painel BuyGoods/fasttrack37) com o CPC que ela paga no Taboola.
- Nenhuma venda desde o lançamento (18/09). Com o volume de cliques no botão ainda baixo (13), ainda é cedo pra julgar a oferta em si.

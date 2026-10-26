---
id: lua-ou-luau
title: "Lua ou Luau?"
description: "Lua ou Luau: Qual escolher, e quais são as diferenças?"
date: "2026-10-26"
category: dev
banner: "images/posts/lua_vs_luau.png"
featured: false
draft: false
badges:
tags:
authors:
  - "@Victor Botelho A."
buttons:
  - label: "Lua"
    link: "https://lua.org"
  - label: "Luau"
    link: "https://luau.org"
---

Lua ou Luau?

Ambas linguagens são muito parecidas, mas possuem muitas diferenças.

Lua (criada no Brasil, na PUC-rio) é uma linguagem de programação leve, simples e fácil  de se utilizar. Com foco total em embedding, se tornou muito utilizada para desenvolvimentos de jogos. Como World of Warcraft, Balatro, Angry Birds, Roblox e diversos outros títulos.

Posso descrever Lua como uma linguagem que caminha com Python em questão de simplicidade. Lua possui uma VM própria, baseada em registradores, para melhor desempenho na execução.

Criada em C, conversa muito bem com aplicações C e C++.

Já o Luau (derivado do Lua 5.1), trás novas propostas para a linguagem. Criado pela Roblox Corporation, o superset traz tipagem gradual, novos conceitos, ferramentas, segurança e desempenho. O Luau é interpretado pela sua própria máquina virtual e JIT (quando disponível). Seu desempenho pode se encontrar superior ao desempenho do Lua tradicional, com seu grande foco em otimizações.

Luau trouxe como principal proposta, o sistema de tipagem. A tipagem é opcional, e deixa o ambiente bem mais seguro de se trabalhar, principalmente entre equipes.

Luau também está trazendo os conceitos modernos, se aproximando mais das linguagens modernas.

Construído inteiramente em C++, também é totalmente compatível com aplicações C, e possui uma API C semelhante a do Lua.

Qual escolher?

Escolha Lua se você procura uma linguagem minimalista, madura e extremamente flexível, especialmente para integrar scripts a aplicações desenvolvidas em C ou C++. Sua simplicidade, portabilidade e facilidade de embedding fazem dela uma excelente opção para jogos, ferramentas e sistemas extensíveis.

Escolha Luau se você procura uma evolução da experiência de desenvolvimento com Lua, especialmente se valoriza tipagem gradual, análise estática, ferramentas de desenvolvimento e otimizações voltadas para ambientes modernos. É uma ótima escolha para projetos no Roblox, mas também pode ser utilizada fora dele, em aplicações próprias.

Não existe uma escolha universalmente melhor: existe a linguagem mais adequada para o seu projeto.

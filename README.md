# Vinheria Agnello — site estático (HTML + CSS)

Este repositório contém o website público da **Vinheria Agnello**, publicado via GitHub Pages. O projeto reúne landing page e páginas internas com navegação simples, conteúdo institucional, tabela de harmonização e vitrines de rótulos.

> **Demo**
>
> ```
> https://gonzales-jpg.github.io/Vinheria_Agnello/index.html
> ```

---

## Estrutura de pastas (projeto)

```
/
├── index.html
└── src/
    ├── pages/
    │   ├── pagina1.html          # Tabela de Harmonização
    │   ├── pagina2.html          # Carrinho (estático)
    │   ├── pagina3.html          # Sobre Nós (história)
    │   ├── pagina4.html          # Clube dos Vinhos
    │   ├── pagina5.html          # Login/Registrar-se
    │   ├── chatue.pagina.html    # Produto – Chateau Grand Puy Lacoste
    │   ├── espumante.pagina.html # Prodito - Salton Moscatel
    │   ├── branco2.pagina.html   # Produto - Concha y Toro Casillero Del Diablo
    │   ├── branco.pagina.html    # Produto - Sauvignon Blanc
    │   ├── bordro2.pagina.html   # Produto - Gran Reserva Concha y Toro
    │   ├── bordo.pagina.html     # Produto - Pérgola Bordô
    │   ├── rose.pagina.html      # Produto - Casal Garcia Rosé
    │   └── rose2.pagina.html     # Produto - Toro Loco Rose
    │
    ├── css
    │    ├── style.css
    │    ├── pagina1.style.css
    │    ├── pagina2.style.css
    │    ├── pagina3.style.css
    │    ├── pagina4.style.css
    │    ├── pagina5.style.css
    │    ├── confirmacao.css
    │    └── comprar.pagina.css
    │
    └── assets/
        └── imgs/
            ├── casillero-del-diablo.web
            ├── bordo.png
            ├── espumante.jpg
            ├── toro-loco-rose.jpg
            ├── bordo-2.jpg
            ├── branco.jpg
            ├── branco-2.jpg
            ├── Chateau-Grand.jpg
            ├── Confirmado.gif
            ├── image-0.webp
            ├── rose.jpg
            ├── vinho-de-mesa-ou-vinho-fino-2-blog-setembro-22
            └── LOGO.png
```

Observação: as folhas de estilo (CSS) estão versionadas no repositório; a barra de linguagens do GitHub indica HTML e CSS como tecnologias predominantes.

---

##  Navegação & seções

- **Header** com links: *Clube de Vinhos*, *Sobre Nós*, *Login/Registrar-se*, *Vídeos* (YouTube), *Carrinho* e *Tabela de Harmonização*.
- **Home** com imagem de capa e a seção **“Mais vendidos”** (grade de produtos).
- **Rodapé** com aviso de direitos autorais.

---

##  Conteúdo institucional (resumo)

A Vinheria Agnello é um negócio familiar de São Paulo, com mais de 15 anos no mercado, que cresceu mantendo atendimento consultivo. A gestão é feita por **Giulio** (fundador) e **Bianca** (filha), apoiados por uma equipe enxuta de seis pessoas e por um ERP que integra finanças, compras e estoque. Há cuidado específico com armazenagem para preservar rótulos de maior valor (luz, calor e vibração sob controle).

---

##  Clube dos Vinhos (resumo)

Plano com **2 garrafas por mês**, curado pelo sommelier **Rodrigo Colon**, priorizando rótulos com **ótimo custo‑benefício** e vínculo temático — regiões, uvas e estilos. Os envios do clube ocorrem até o **dia 15** de cada mês (o primeiro envio acontece no mês seguinte ao pagamento) e **o cancelamento é livre**. O clube também envia conteúdos sobre o tema do mês e o processo de escolha dos rótulos.

---

##  Tabela de harmonização (resumo)

- **Espumante Brut** → entradas leves; queijos frescos; frituras  
- **Sauvignon Blanc** → saladas; peixes; culinária japonesa  
- **Chardonnay (sem madeira)** → frango grelhado; risotos mais leves  
- **Chardonnay (com madeira)** → massas ao molho branco; carnes brancas  
- **Pinot Noir** → aves; cogumelos; massas ao molho vermelho  
- **Merlot** → carnes magras; pizzas; queijos de média intensidade  
- **Cabernet Sauvignon** → carnes vermelhas; cordeiro  
- **Malbec** → churrasco; queijos curados; carnes assadas  
- **Porto / Moscatel** → sobremesas; chocolate; frutas secas  

 A lista acima resume a tabela apresentada na página de harmonização do site.

---

##  Imagens usadas (pasta `src/assets/imgs/`)

- `vinho-de-mesa-ou-vinho-fino-2-blog-setembro-22.jpg` – imagem de capa (vinhos tinto e branco em taças).  
- `bordo.png` – garrafa Pérgola Bordô.  
- `espumante.jpg` – garrafa de espumante Salton Moscatel (imagem de produto).  
- `toro-loco-rose.jpg` – garrafa Toro Loco Rosé (imagem de produto). 
- `bordo-2.jpg` – garrafa Concha y Toro Gran Reserva(imagem de produto).  
- `branco.jpg` – garrafa de vinho branco (imagem de produto).  
- `branco-2.jpg` – garrafa de vinho branco (imagem de produto).  
- `rose.jpg` - garrafa de vinho rose (imagem de produto).
- `image-0.webp` - garrafa de vinho gran reserva (imagem de produto).
- `confirmado.gif` - gif de check.
- `Chatue-Grand.jpg` - garrafa de vinho Chatue Grand (imagem de produto).
- `casillero-del-diablo.webp` - garrafa de vinho bordô (imagem de produto).
- `LOGO.png` - Logo da empresa

 **Uso de marcas/imagens**: as imagens são meramente ilustrativas e pertencem aos respectivos titulares. Mantenha créditos e direitos conforme aplicável.

---

##  Tecnologias

- **HTML5** e **CSS3** (sem back‑end).

---

## Executar localmente

1. Clone o repositório e abra o projeto na sua máquina.  
2. Abra o arquivo `index.html` diretamente no navegador (duplo clique ou via servidor local).

> Opcional: use uma extensão de *Live Server* para auto‑reload durante a edição.

---

##  Deploy (GitHub Pages)

1. No repositório, acesse **Settings › Pages**.  
2. Em **Source**, escolha **Deploy from a branch**.  
3. Selecione **branch** (ex.: `main`) e a **pasta** (`/` para raiz ou `docs/`, se aplicável).  
4. Salve. Aguarde a publicação em uma URL do tipo: `https://USUÁRIO.github.io/NOME_DO_REPO/`.

Para projetos que usam pastas como `docs/` ou geradores estáticos (ex.: Jekyll/Quarto), adicione um arquivo `.nojekyll` na raiz para evitar o processamento automático.

---

## Status & limitações

- Páginas internas estáticas (ex.: *Carrinho* apenas ilustrativo).  
- Link de **Vídeos** abre conteúdo externo (YouTube).  
- Página de produto de exemplo: **Chateau Grand Puy Lacoste 750ml** com preço exibido.

---

## Roadmap (ideias de evolução)

- Carrinho funcional com JavaScript + `localStorage` (ou back‑end leve).  
- Página de **produto** mais completa (descrição, ficha técnica, avaliações).  
- Catálogo dinâmico (JSON/API fake) e filtros por uva, país, faixa de preço.  
- Ajustes de **acessibilidade** (contraste, navegação por teclado, `aria-*`).  
- **SEO**: `<title>`, `meta description`, Open Graph/Twitter Cards e favicon.  
- Otimização de imagens (compressão, formatos modernos e `loading="lazy"`).

---

## Licença

Nenhum arquivo de licença.

---

## Créditos

Projeto educacional/demonstração. Conteúdos de terceiros (marcas, rótulos, imagens) permanecem com seus respectivos proprietários.

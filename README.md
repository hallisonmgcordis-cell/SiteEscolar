# Projeto Website - E. E. Paulina Rigotti de Castro

Este projeto foi desenvolvido como parte do Plano de Trabalho das **Práticas de Extensão II (PEII)** do **IFSULDEMINAS - Campus Machado**.

## 👥 Equipe de Desenvolvimento
- Victor Hugo Caproni Silva Costa
- João Eduardo Silva
- Hallison Maria Januário
- Tobias Pereira

## 🛠️ Tecnologias Utilizadas
- **HTML5 & JavaScript Vanilla (SPA - Single Page Application)**
- **Tailwind CSS** (via CDN para responsividade e suporte a Alto Contraste)
- **FontAwesome** (Ícones de acessibilidade e navegação)
- **Google Planilhas (CSV publicado)** (Fonte dos avisos e eventos)
- **Google Maps (iframe incorporado)** (Mapa de localização)

## 📌 Funcionalidades
1. **Página Inicial:** Banner de boas-vindas, cards de acesso rápido e mural de avisos/eventos carregado da planilha pública.
2. **Sobre a Instituição:** Missão, visão, valores, histórico institucional e apresentação da equipe/direção.
3. **Contato e Localização:** Formulário de envio de mensagem com feedback interativo e mapa incorporado do Google Maps.
4. **Recursos de Acessibilidade:**
   - Botões de ajuste dinâmico do tamanho do texto (A-, A, A+).
   - Modo de Alto Contraste funcional.
   - Estrutura HTML semântica com suporte a leitores de tela.

## 🚀 Como Executar
Sirva a pasta por um servidor web local (por exemplo, a extensão Live Server do VS Code) e abra o endereço local no navegador. Como o mural carrega a planilha com `fetch()`, abrir `index.html` diretamente como arquivo (`file://`) pode ser bloqueado pelo navegador.

Os avisos são lidos da planilha publicada em CSV. Mantenha na primeira linha as colunas `Titulo`, `Tipo`, `data` e `resumo`; cada linha seguinte representa um aviso ou evento. O conteúdo publicado fica acessível publicamente.

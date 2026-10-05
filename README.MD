# De frente com o QA

![Capa do podcast De frente com o QA](assets/cover.png)

**De frente com o QA** é um projeto de podcast sobre qualidade de software, testes e tecnologia. A proposta é compartilhar conversas e conteúdos curtos, acessíveis para quem está começando em QA e para pessoas desenvolvedoras que querem entender melhor a qualidade ao longo do desenvolvimento.

O repositório reúne prompts usados como apoio à criação do podcast, além de materiais visuais e um exemplo de áudio. Ele não é uma aplicação executável nem automatiza a geração de episódios.

## Sobre o podcast

- **Apresentação:** João
- **Público:** iniciantes em QA e pessoas desenvolvedoras em geral
- **Temas:** testes de software, qualidade, automação de testes, performance, carreira e o cenário de QA
- **Abordagem:** conteúdo breve, direto e introdutório, sem aprofundamento excessivo em um único assunto
- **Tecnologia e IA:** discussão sobre o mercado de QA e os impactos da inteligência artificial no trabalho e na automação

## Estrutura do repositório

```text
.
├── assets/
│   └── cover.png                 # Capa do podcast
├── output/
│   └── audioPodCast.mp3          # Exemplo de episódio em áudio
├── src/
│   └── prompts/
│       └── chatgpt.md            # Prompts para nome, identidade visual e roteiro
└── .github/
    └── assets/
        └── banner.png            # Banner do projeto
```

## Como funciona

1. **Definição da identidade:** o prompt em [`src/prompts/chatgpt.md`](src/prompts/chatgpt.md) orienta a criação de sugestões de nome e subtítulo para o podcast.
2. **Criação visual:** o mesmo arquivo contém uma orientação para criar uma capa temática. A imagem disponível no projeto está em [`assets/cover.png`](assets/cover.png).
3. **Preparação do roteiro:** o prompt propõe episódios curtos organizados em quatro partes:
   - **Introdução**
   - **Curiosidade 1:** contexto geral e importância de QA no desenvolvimento
   - **Curiosidade 2:** informações sobre ferramentas usadas em automação
   - **Finalização:** despedida do apresentador e encerramento do episódio
4. **Revisão e produção:** use os prompts em uma ferramenta de IA compatível, revise o conteúdo gerado e produza a gravação com as ferramentas de sua preferência. A geração de texto, imagem e áudio acontece fora deste repositório.
5. **Exemplo de áudio:** [`output/audioPodCast.mp3`](output/audioPodCast.mp3) contém um arquivo de áudio de exemplo incluído no projeto.

## Como usar os prompts

1. Abra [`src/prompts/chatgpt.md`](src/prompts/chatgpt.md).
2. Escolha o prompt que deseja usar (nome, capa ou roteiro) e copie-o para uma ferramenta de IA.
3. Informe o tema do episódio e ajuste as instruções conforme necessário.
4. Revise nomes de ferramentas, informações técnicas e demais afirmações antes de gravar.
5. Grave e exporte o episódio com uma ferramenta de áudio. O repositório não define uma ferramenta específica para essa etapa.

## Executar o projeto

Não há instalação ou comando de execução: o conteúdo deste repositório é composto por prompts e arquivos de mídia. Para contribuir com um episódio, atualize ou acrescente os materiais correspondentes e mantenha os prompts alinhados com a proposta do podcast.
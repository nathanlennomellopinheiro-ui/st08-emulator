# st08-emulator

🟢 ST.08 Emulator | PS2 Experimental

Gaming Like a Beast. Building Beyond Limits.

Uma interface experimental de emulação inspirada no PlayStation 2, desenvolvida com HTML, CSS e JavaScript, com foco em análise de arquivos, interface web e futura integração com um motor de emulação real.

«Status: Experimental. A interface e o analisador básico de arquivos estão implementados. A emulação real de jogos de PS2 ainda não está integrada.»

---

⚡ Sobre o projeto

O ST.08 Emulator é um projeto experimental criado para explorar o desenvolvimento de interfaces de emulação diretamente no navegador.

Com uma estética gamer inspirada em 2016, terminais hacker e interfaces verde-neon, o projeto busca unir identidade visual, ferramentas de diagnóstico e experimentação com tecnologias web.

Principais recursos

- 🟢 Interface responsiva com tema hacker verde-neon.
- 📁 Seleção de arquivos ISO diretamente do dispositivo.
- 🔍 Leitura de informações básicas, como nome, tamanho e extensão.
- 💿 Verificação básica da assinatura ISO 9660 no setor esperado.
- 🖥️ Painel de estado do sistema experimental.
- 📟 Terminal de diagnóstico com mensagens geradas pelas verificações reais.
- 🌐 Estrutura compatível com hospedagem estática, incluindo GitHub Pages.
- 🧩 Base visual preparada para uma futura integração com WebAssembly.

🛠️ Tecnologias

Tecnologia| Utilização
HTML5| Estrutura da interface
CSS3| Layout, efeitos neon e responsividade
JavaScript| Seleção de arquivos e análise de cabeçalhos
WebAssembly| Tecnologia prevista para uma possível integração do motor
GitHub Pages| Hospedagem estática do site

🚀 Como executar

Opção 1: abrir localmente

1. Baixe o arquivo HTML do projeto.
2. Abra-o em um navegador moderno.
3. Utilize o botão ESCOLHER ISO para selecionar um arquivo.
4. Consulte os metadados e as mensagens do terminal.

Opção 2: publicar no GitHub Pages

1. Envie o arquivo principal para a raiz do repositório.
2. Certifique-se de que ele se chama "index.html".
3. Abra Settings → Pages no GitHub.
4. Configure a publicação pela branch principal e pela pasta "/ (root)".
5. Aguarde a publicação e acesse o endereço fornecido pelo GitHub Pages.

💿 Sobre a análise de ISO

O analisador verifica informações básicas do arquivo selecionado e procura uma assinatura ISO 9660 no deslocamento padrão do descritor primário de volume.

Essa verificação é limitada: encontrar a assinatura não comprova que a imagem seja um jogo válido de PS2. Da mesma forma, não encontrar a assinatura no local esperado não prova que o arquivo seja inválido.

O projeto ainda não interpreta integralmente o formato dos discos de PS2.

🧩 Estado da emulação

O ST.08 Emulator está em fase experimental.

Atualmente, a interface não executa jogos de PlayStation 2. Não há um motor de emulação funcional integrado nesta versão.

Uma futura implementação poderá investigar:

- Integração de um motor de emulação compatível com WebAssembly.
- Comunicação entre a interface web e o núcleo de emulação.
- Renderização gráfica e gerenciamento de controles.
- Compatibilidade entre navegadores e dispositivos.
- Diagnóstico de erros e limitações de desempenho.

Esses itens são objetivos de desenvolvimento, não funcionalidades já concluídas.

🔐 Segurança e uso responsável

- Os arquivos selecionados são analisados localmente pelo navegador.
- Esta versão não envia as imagens ISO para um servidor.
- O arquivo selecionado não é executado pelo analisador.
- O projeto não inclui BIOS ou firmware proprietário de consoles.
- Utilize arquivos que você tenha autorização para usar e respeite a legislação aplicável.

📌 Objetivo

Desenvolver gradualmente uma plataforma web experimental para estudar interfaces de emulação, inspeção de arquivos e integração com tecnologias de baixo nível.

O objetivo é evoluir o projeto com transparência técnica, documentando o que funciona, o que está em desenvolvimento e quais limitações ainda precisam ser resolvidas.

👨‍💻 Desenvolvedor

Nathan Lenno
Projeto: ST.08 Emulator
Categoria: Experimental Web Emulation Interface

---

🟢 ST.08 Emulator | PS2 Experimental

Gaming Like a Beast. Building Beyond Limits.

Uma interface experimental de emulação inspirada no PlayStation 2, desenvolvida com HTML, CSS e JavaScript, com foco em análise de arquivos, interface web e futura integração com um motor de emulação real.

«Status: Experimental. A interface e o analisador básico de arquivos estão implementados. A emulação real de jogos de PS2 ainda não está integrada.»

---

<p align="center">
  <strong>ST.08 EMULATOR</strong><br>
  <code>GAMING LIKE A BEAST // BUILDING BEYOND LIMITS</code>
</p>
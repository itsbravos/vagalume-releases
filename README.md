# Lightning Bug (Vagalume)

Seu assistente no topo do Windows: fica numa ilha no alto da tela, substitui a barra de tarefas, abre um painel com o que se usa o dia todo e atende por voz, com a sua própria chave de IA ou um modelo rodando no computador.

**Baixar:** abra a [última versão](https://github.com/itsbravos/vagalume-releases/releases/latest) e, em **Assets**, clique em `Vagalume-Setup-<versão>.exe`. Depois de instalado, o Vagalume se atualiza sozinho. Windows 10 ou 11, 64 bits.

Este repositório guarda só os instaladores.

## O que ele faz

### A barra no topo

- **Substitui a barra de tarefas** do Windows (ou convive com ela): uma pílula com o vagalume e a hora que, ao passar o mouse, vira uma faixa e, ao rolar, um painel.
- **Na faixa:** botão Iniciar, pontos das áreas de trabalho, apps fixados e abertos (com prévia ao vivo das janelas e Win+1 a Win+9), o que está tocando, rede, CPU, RAM, temperatura, bateria, som, perfil de uso, aviso de desligamento agendado, temporizador, bandeja do sistema e relógio com a central de notificações. Quando falta espaço, o que é menos importante sai primeiro; música, som e relógio nunca somem.
- **Tecla Windows** abre o lançador; o menu Iniciar continua no ícone do Windows. Cantos ativos da tela fazem uma ação ao encostar o mouse.
- **Em tela cheia** ele se esconde (ou fica só a pílula). Quatro visuais (Âmbar, Lanterna, Xilogravura, Cyberpunk), sete vagalumes e cor tirada do papel de parede. Português, inglês e espanhol.

### Voz e IA

- **Ditado** (segure `Ctrl`+`Win`), **assistente** (segure `Ctrl`+`Alt`) e **circular e perguntar** (segure `Ctrl`+`Shift` e circule algo na tela).
- **Ler a tela:** "o que diz esse erro?" olha só a janela da frente, uma vez, sem guardar print.
- **Chamar pelo nome** ("Vagalume, abre o Spotify"), conversa que continua sozinha quando ele pergunta algo, memória do que você contou, notas, resumo do dia, agenda por link iCal (Google, Outlook, iCloud…).
- **Sua chave de IA:** Gemini, Claude, GPT e Grok, várias ao mesmo tempo, com reservas; ou um modelo local pelo Ollama. Com a fala local (Whisper), funciona inteiro **sem internet**.
- **Pela voz:** abrir apps, sites e arquivos; buscar; música e volume; brilho; modo escuro; Wi-Fi e Bluetooth; janelas; captura de tela; temporizador; tarefas; lembretes; perfis; rotinas.

### Lançador (tecla Windows)

- Apps com favoritos, pastas, filtros e as páginas de configuração do Windows; tolera uma letra trocada.
- **Arquivos pelo nome na hora**, em todos os discos (com índice rápido pela tabela do NTFS, como o Everything). **Espaço** mostra a prévia (PDF, imagem, texto, áudio, vídeo, pasta) sem abrir o programa.
- **Contas** (`= 15% de 320`), **câmbio** (`100 dólares em reais`), **comando** visível no terminal (`> ipconfig`), **desligar ou reiniciar mais tarde** (`desligar em 30 min`), **busca na web** (`? termo`).

### Painel

- **Controles:** rede, Wi-Fi, Bluetooth, som, modo escuro, captura, notificações; volume geral e por app; microfone; **brilho de cada monitor** (inclusive externos, por DDC/CI) e **luz noturna** por horário ou do pôr ao nascer do sol; o que está tocando.
- **Hoje:** relógio, clima, semana e mês com feriados, pomodoro com modo foco, tarefas, agendados e rotinas.
- **Stats:** processador, memória, rede, temperaturas, modo de energia e discos. Um clique no disco mostra **o que ocupa o espaço** (pastas, maiores arquivos, tipos) e uma **limpeza com prévia** de tudo o que sai.
- **Processos:** os que mais pesam, com encerrar. **Rede:** Wi-Fi, VPN, velocidade do link, modo avião, QR do Wi-Fi e os aparelhos da rede local.
- **Clipboard** (textos e imagens, também no Win+V), **Notas**, **Apps**, **Papéis** de parede e **Energia**.

### Janelas

- **Arranjo automático:** Mosaico (como o Hyprland) ou Faixa infinita de colunas (como o niri, com Win + roda do mouse e minimapa na barra).
- **Zonas:** desenhe zonas por monitor e encaixe as janelas arrastando com Shift, como o FancyZones.
- **Áreas de trabalho:** trocar, criar, renomear e fechar pela barra; levar uma janela para outra área arrastando a prévia; cada área guarda o seu arranjo.

### Automação

- **Perfis de uso** (Foco, Jogo e os seus): silenciar, modo de energia, volume, papel de parede, barra reduzida, fechar e pausar apps. Ligam por clique, voz, horário ou quando um jogo entra em tela cheia; ao desligar, tudo volta como estava.
- **Rotinas:** "quando eu desbloquear de manhã, abre o e-mail e a agenda". Disparam por horário, primeiro desbloqueio do dia, aparelho Bluetooth, rede Wi-Fi ou app aberto, e são confirmadas antes de salvar.
- **Agendados:** "me lembra de ligar pra mãe às seis", "todo dia às nove abre o Unity".

### Sistema

- Atualiza sozinho, abre com o Windows e guarda as chaves criptografadas (DPAPI).
- Ajustes rápidos do Windows e histórico do Win+V do próprio Vagalume, que pode ser limpo ao desligar.

---

# English

Your assistant on top of Windows: it lives in an island at the top of the screen, stands in for the taskbar, opens a panel with what you use all day and takes requests by voice, with your own AI key or a model running on your computer.

**Download:** open the [latest release](https://github.com/itsbravos/vagalume-releases/releases/latest) and, under **Assets**, click `Vagalume-Setup-<version>.exe`. Once installed, Vagalume updates itself. Windows 10 or 11, 64-bit.

This repository only holds the installers.

## What it does

### The bar on top

- **Replaces the Windows taskbar** (or lives alongside it): a pill with the firefly and the time that becomes a strip when the mouse is over it, and a panel when you scroll.
- **On the strip:** Start button, virtual desktop dots, pinned and open apps (with live window previews and Win+1 to Win+9), what is playing, network, CPU, RAM, temperature, battery, sound, usage profile, a planned shutdown, a timer, the system tray and a clock with the notification centre. When room runs out, the least needed go first; music, sound and the clock always stay.
- **The Windows key** opens the launcher; the Start menu is still on the Windows icon. Hot corners run an action when the mouse touches them.
- **In full screen** it hides (or keeps only the pill). Four looks (Amber, Lantern, Woodcut, Cyberpunk), seven fireflies and a colour taken from the wallpaper. Portuguese, English and Spanish.

### Voice and AI

- **Dictation** (hold `Ctrl`+`Win`), **assistant** (hold `Ctrl`+`Alt`) and **circle to ask** (hold `Ctrl`+`Shift` and circle something on screen).
- **Read the screen:** "what does this error say?" looks only at the window in front, once, and keeps no picture.
- **Call it by name** ("Vagalume, open Spotify"), a conversation that goes on by itself when it asks you something, a memory of what you told it, notes, a summary of your day, calendars by iCal link (Google, Outlook, iCloud…).
- **Your own AI key:** Gemini, Claude, GPT and Grok, several at once, with fallbacks; or a local model through Ollama. With local speech (Whisper) it works **fully offline**.
- **By voice:** open apps, sites and files; search; music and volume; brightness; dark mode; Wi-Fi and Bluetooth; windows; screenshots; timers; tasks; reminders; profiles; routines.

### Launcher (Windows key)

- Apps with favourites, folders, filters and the Windows settings pages; forgives a wrong letter.
- **Files by name, instantly**, on every drive (with a fast index read from the NTFS table, like Everything). **Space** previews them (PDF, picture, text, audio, video, folder) without opening their program.
- **Maths** (`= 15% of 320`), **currency** (`100 usd in eur`), a **command** in a visible terminal (`> ipconfig`), **shut down or restart later** (`shutdown in 30 min`), **web search** (`? term`).

### Panel

- **Controls:** network, Wi-Fi, Bluetooth, sound, dark mode, screenshot, notifications; master and per-app volume; microphone; **each monitor's brightness** (external ones too, over DDC/CI) and a **night light** by the clock or from sunset to sunrise; what is playing.
- **Today:** clock, weather, week and month with holidays, a pomodoro with focus mode, tasks, scheduled items and routines.
- **Stats:** processor, memory, network, temperatures, power mode and drives. Clicking a drive shows **what takes the space** (folders, largest files, kinds) and a **cleanup that shows everything it removes** first.
- **Processes:** the heaviest, with end task. **Network:** Wi-Fi, VPN, link speed, airplane mode, a Wi-Fi QR code and the devices on your local network.
- **Clipboard** (text and pictures, also on Win+V), **Notes**, **Apps**, **Wallpapers** and **Power**.

### Windows

- **Automatic arrangement:** Tiling (like Hyprland) or an endless Strip of columns (like niri, with Win + mouse wheel and a minimap in the bar).
- **Zones:** draw zones per monitor and snap windows by dragging with Shift, like FancyZones.
- **Virtual desktops:** switch, create, rename and close from the bar; move a window to another desktop by dragging its preview; each desktop keeps its own arrangement.

### Automation

- **Usage profiles** (Focus, Gaming and your own): silence, power mode, volume, wallpaper, a reduced bar, closing and pausing apps. They start by a click, your voice, the clock or a game going full screen; turning one off puts everything back.
- **Routines:** "when I unlock in the morning, open my email and calendar". They start by the clock, the first unlock of the day, a Bluetooth device, a Wi-Fi network or an app opening, and are confirmed before they are saved.
- **Scheduled tasks:** "remind me to call mum at six", "every day at nine open Unity".

### System

- Updates itself, starts with Windows and keeps your keys encrypted (DPAPI).
- Quick Windows tweaks and Vagalume's own Win+V history, which can be cleared at shutdown.

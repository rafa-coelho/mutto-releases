# Mutto

**Um botão para o seu microfone, em qualquer app.** Um atalho, ou um toque no celular, silencia o microfone e desliga a câmera em qualquer app de chamada no Windows 11.

[![Mutto](https://www.mutto.app/assets/pt/filme.jpg)](https://www.mutto.app)

Site: **[mutto.app](https://www.mutto.app)**

## Instalar

Use o site, que escolhe a versão certa para o seu PC, ou rode no PowerShell:

```powershell
irm https://www.mutto.app/mutto/install.ps1 | iex
```

## Por dentro

- **C# / .NET 10** para Windows 11, com builds x64 e ARM64
- Atalho global (Ctrl+Shift+M) que funciona igual no Teams, Meet, Zoom, Discord ou qualquer outro app
- Também dá para mutar com um toque no celular
- Núcleo compartilhado com o [Doca](https://github.com/rafa-coelho/doca-releases): licença, idiomas, atalhos globais e atualização automática

## Este repositório

O código do Mutto é privado. Aqui ficam só os instaladores: cada [release](https://github.com/rafa-coelho/mutto-releases/releases) tem os setups x64 e ARM64, o arquivo de versão e o changelog. As versões marcadas como pré-lançamento são do beta fechado.

---

**Mutto** mutes your microphone (and turns off the camera) in any call app on Windows 11, from a global shortcut or a tap on your phone. Built in C# / .NET 10. This repository hosts installers and release notes only; see [mutto.app](https://www.mutto.app).

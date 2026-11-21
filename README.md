# 🚀 PC Performance Lab

**Diagnóstico, monitoramento e otimização para o seu Windows.**

O PC Performance Lab é uma plataforma desktop que reúne monitoramento de hardware em tempo real, diagnóstico local e ajustes seguros do sistema. Você pode observar o computador e gerar relatórios sem aplicar nenhuma otimização.

---

## 📥 Download

[**Baixar a versão mais recente**](https://github.com/jcfms/performance-lab-releases/releases/latest)

1. Acesse a página de releases.
2. Na seção **Assets**, baixe o instalador (`PerformanceLab-Setup.exe`).
3. Execute o instalador como **Administrador**.

---

## ⚙️ Requisitos

- **Sistema:** Windows 10 ou 11 (64 bits).
- **Permissões:** Administrador (necessário para aplicar otimizações no sistema).
- **WebView2 Runtime:** O instalador já inclui o runtime necessário.

---

## 🛡️ Sobre o aviso do Windows

O Windows pode exibir um aviso de "Aplicativo não reconhecido" durante a instalação, porque o instalador usa um **certificado autoassinado**. Isso é esperado para projetos independentes.

Para prosseguir:
1. Clique em **"Mais informações"**.
2. Clique em **"Executar assim mesmo"**.

O código-fonte é aberto e o app não coleta dados pessoais.

---

## ✨ Funcionalidades

- **Dashboard em tempo real:** CPU, GPU, RAM, Disco e Rede.
- **Diagnóstico:** Análise de armazenamento, memória, temperaturas, drivers e rede.
- **Otimização do Windows:** Serviços, energia, telemetria, Core Parking e HAGS.
- **Debloat Seguro:** Desativa apps pré-instalados sem removê-los.
- **Limpeza Inteligente:** Temporários, Prefetch, Lixeira e RAM.
- **Rede e Input Lag:** Ajustes de TCP, USB e prioridade de processos.
- **Gaming:** Biblioteca de jogos, perfis e ajustes automáticos.

---

## 🧩 Tecnologias

- **Backend:** C# / .NET 10
- **Frontend:** HTML, CSS, JavaScript (WebView2)
- **Hardware:** LibreHardwareMonitor + PawnIO
- **Comunicação:** Bridge C# ↔ JavaScript

---

## 📄 Licença

Este projeto é distribuído para uso pessoal e comercial. Consulte o arquivo `LICENSE` para mais detalhes.

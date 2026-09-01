Base de conhecimento inteligente desenvolvida para consulta rápida e aprendizado continuo de agentes de suporte técnico de nível 1.

---

## 🎯 Contexto e Objetivos

* **Uso:** Suporte à atualização de sistemas operacionais (Windows e macOS).
* **Proposta:** Base de conhecimento para consulta rápida de agentes de suporte técnico de nível 1.
* **Objetivos:** 
  * Aumentar a satisfação do cliente por meio de interações mais fluidas, precisas e menos demoradas.
  * Reduzir a frustração do responsável pelo atendimento, fornecendo respostas certeiras de forma ágil e permitindo que ele aprenda o conteúdo mais a fundo.

---

## 📑 Curadoria de Fontes

A base de conhecimento foi construída a partir da combinação de documentações oficiais e tutoriais práticos em vídeo:

### 🎥 Fontes de Vídeo
* [Vídeo 1 - Atualização do Windows 10 para o 11](https://youtu.be/MHr36i7rj9s?si=x73uejXFha2E7SWc)
* [Vídeo 2 - Atualização do Windows 7 para o Windows 10](https://youtu.be/HZsft13GoXc?si=TbRIJwPc8nVevY12)
* [Vídeo 3 - Atualizar Macs Antigos para o macOS Recente](https://youtu.be/PHsEgcljVyM?si=vkSWUjWyX-dPvXSF)
* [Vídeo 4 - Atualizar o Sistema do MacBook, Mac Mini e iMac](https://youtu.be/66fQM0KSXtQ?si=MU94wUE6DVSFflQO)

### 📄 Fontes de Texto / Artigos Oficiais
* [Apple Support - Atualizar o macOS no Mac](https://support.apple.com/pt-br/108382)
* [Apple Support - Guia do Usuário do macOS: Atualizações de Software](https://support.apple.com/pt-br/guide/mac-help/mchlpx1065/mac)
* [Microsoft Learn - Instalar Atualizações do Windows](https://support.microsoft.com/pt-br/windows/deployment/updates-lifecycle/install-windows-updates)
* [Microsoft Learn - Obter Atualizações do Windows Assim que Estiverem Disponíveis](https://support.microsoft.com/pt-br/windows/deployment/updates-lifecycle/get-windows-updates-as-soon-as-they-re-available-for-your-device)
* [Apple Support - Segurança do macOS: Gatekeeper e Proteção de Aplicativos](https://support.apple.com/pt-br/guide/security/sec5599b66df/web)

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção são documentados os testes de prompts realizados, os desafios identificados no modelo de IA e as soluções aplicadas para garantir respostas precisas no atendimento.

### 🧪 Prompts Testados e Análise

* **Prompt V1:** *"Como eu sei se deveria atualizar meu sistema?"*
  * **Análise:** A resposta foi muito abrangente. A IA citou diversas fontes, mas não direcionou exatamente sobre qual sistema operacional se tratava nem focou no contexto do atendimento.

* **Prompt V2:** *"Se eu baixar a atualização do sistema porém o Gatekeeper me impedir de continuar, o que devo fazer?"*
  * **Dificuldade Encontrada:** Inicialmente, as fontes selecionadas no projeto não mencionavam diretamente o recurso **Gatekeeper** nem como proceder especificamente caso ele bloqueasse a instalação de uma atualização.
  * **Ajuste Aplicado:** Foi adicionada uma nova fonte oficial de documentação da Apple referente à segurança do macOS e Gatekeeper (`https://support.apple.com/pt-br/guide/security/sec5599b66df/web`), e a pergunta foi ajustada/refeita dentro desse novo contexto.
  * **Resultado Refinado:** A IA passou a gerar uma resposta totalmente condizente com a pergunta, citando o passo a passo recomendado pelo suporte oficial da marca de forma clara e estruturada.

---

## 📖 Miniguia de Estudo (Entrega Final)

Este guia consolida as orientações de atualização e conceitos essenciais para o agente N1.

### 1. 🚀 Como Atualizar o macOS e Windows (Versões Novas e Antigas)

#### 🍎 Atualização de Dispositivos Apple (macOS & iOS via Finder)
* **Pelo próprio Mac:** Acesse *Ajustes do Sistema > Geral > Atualização de Software*.
* **iPhone via Finder no Mac:**
  1. Conecte o iPhone ao Mac via cabo USB/Lightning.
  2. Abra o **Finder** e selecione o dispositivo na barra lateral esquerda.
  3. Na aba *Geral*, clique em **Buscar Atualização**.
  4. Se houver falha de comunicação, certifique-se de que o Mac está atualizado e de que o cabo é original/certificado.

#### 🪟 Atualização de Sistemas Windows (Windows 10 / 11)
* **Acesso Padrão:** *Configurações > Windows Update > Verificar se há atualizações*.
* **Solução de Problemas Comuns:**
  * Executar a **Solução de Problemas do Windows Update**.
  * Verificar se há espaço em disco suficiente (mínimo recomendado de 20 GB a 30 GB livres para grandes atualizações).
  * Desconectar periféricos desnecessários durante a instalação.

---

### 2. 🔤 Glossário de Conceitos Básicos

| Termo | Definição / Significado Simples |
| :--- | :--- |
| **Finder** | Gerenciador de arquivos do Mac (equivalente ao Explorador de Arquivos do Windows), usado também para gerenciar iPhones conectados. |
| **Windows Update** | Ferramenta nativa do Windows responsável por baixar e instalar correções de segurança e novas versões do sistema. |
| **Gatekeeper** | Tecnologia de segurança do macOS projetada para garantir que apenas softwares confiáveis sejam executados no Mac. |
| **Backup** | Cópia de segurança dos dados e arquivos do cliente feita antes de iniciar qualquer grande atualização. |
| **Driver** | Programa que permite ao sistema operacional se comunicar com os componentes de hardware (placa de vídeo, Wi-Fi, etc.). |
| **Troubleshooting** | Processo sistemático de identificação e solução de problemas técnicos. |

---

### 3. 🎯 Conjunto de Prompts Reutilizáveis para Atendimento

Prompts prontos para o agente copiar, colar e aplicar durante chamadas ou chats:

* **Para Passo a Passo Rápido:**
  > *"Forneça um roteiro de até 4 passos simples para indicar ao cliente como verificar atualizações pendentes no Windows 11."*
* **Para Mensagens de Erro Genéricas:**
  > *"O cliente recebeu o erro [INSERIR CÓDIGO/MENSAGEM DE ERRO] ao atualizar o macOS. Liste as 3 causas mais prováveis e a solução para a mais comum em linguagem acessível."*
* **Para Diagnóstico Pré-Atualização:**
  > *"Quais requisitos prévios devo pedir para o cliente verificar antes de atualizar do Windows 10 para o Windows 11?"*

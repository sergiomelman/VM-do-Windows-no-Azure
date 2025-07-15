# Criação de Máquina Virtual Windows via Portal Azure

Este repositório fornece um guia passo a passo para a criação de uma máquina virtual Windows no Azure, 
com base na [documentação oficial da Microsoft](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal).

## 🧾 Índice

- [Pré-requisitos](#pré-requisitos)
- [Etapas de Criação](#etapas-de-criação)
  - [1. Acessar o Portal do Azure](#1-acessar-o-portal-do-azure)
  - [2. Criar uma nova Máquina Virtual](#2-criar-uma-nova-máquina-virtual)
  - [3. Configurações Básicas](#3-configurações-básicas)
  - [4. Configurações de Disco e Rede](#4-configurações-de-disco-e-rede)
  - [5. Revisar + Criar](#5-revisar--criar)
- [Acessar a VM](#acessar-a-vm)
- [Recursos Úteis](#recursos-úteis)

## 📌 Pré-requisitos

- Conta ativa no Azure
- Permissão para criar recursos
- Navegador atualizado

## 🔧 Etapas de Criação

### 1. Acessar o Portal do Azure

Acesse: [https://portal.azure.com](https://portal.azure.com)

### 2. Criar uma nova Máquina Virtual

1. No menu lateral, clique em **Máquinas Virtuais**
2. Clique em **Criar** > **Máquina virtual**

### 3. Configurações Básicas

Preencha os campos:
- **Assinatura:** selecione sua assinatura ativa
- **Grupo de recursos:** crie ou selecione um existente
- **Nome da VM**
- **Região**
- **Imagem:** Windows Server (ex: 2019 Datacenter)
- **Tamanho da máquina**
- **Usuário e senha de administrador**

### 4. Configurações de Disco e Rede

- Configure disco padrão (SSD recomendável)
- Defina as regras de acesso da rede
- Ative acesso via RDP (porta 3389)

### 5. Revisar + Criar

- Clique em **Revisar + criar**
- Verifique as configurações e clique em **Criar**

## 🖥️ Acessar a VM

Após a implantação:
- Acesse via RDP usando IP público da VM
- Use as credenciais definidas anteriormente

## 📚 Recursos Úteis

- [Documentação Microsoft Azure](https://learn.microsoft.com/pt-br/azure/)
- [Portal de Suporte Azure](https://azure.microsoft.com/pt-br/support/)
- [Exemplos de automação via Azure CLI](https://learn.microsoft.com/pt-br/cli/azure/)

---

Este projeto é ideal para quem deseja iniciar rapidamente no Azure e testar serviços em nuvem com máquinas virtuais Windows. Contribuições são bem-vindas!

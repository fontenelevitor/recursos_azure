# 🧠 Desafio DIO - Configuração de Máquinas Virtuais na Azure

Este projeto faz parte do desafio da **Digital Innovation One (DIO)** sobre configuração e dimensionamento de máquinas virtuais na **Azure**.  
O objetivo é criar uma VM Windows e configurar uma área de trabalho virtual com pool de hosts.

---

## 🚀 Objetivo do Projeto
- Criar e configurar uma máquina virtual com parâmetros específicos.  
- Explorar a área de trabalho virtual com pool de hosts.  

---

## 🧱 Passo a Passo

### Máquina Virtual
- Nome: `machine01`  
- Grupo de Recursos: `AZ-900_Lab_DIO`  
- Região: `East US 2`  
- Tamanho: `Standard_DS1_v2` (1 vCPU, 3.5 GiB RAM)  
- Disco: 127 GiB SSD Premium, excluir com VM  
- Rede: nova padrão, excluir IP público e NIC com VM  
- Segurança: RDP 3389 aberto  
- Gerenciamento: desligamento automático às 19h com notificação por e-mail  
- Backup: desabilitado  
- Monitoramento: sem alertas recomendados, diagnóstico desabilitado  

### Área de Trabalho Virtual
- Grupo de Recursos: `AZ-900_Lab_DIO`  
- Região: `East US`  
- Tipo: Área de trabalho em pool  
- Balanceamento: largura  
- Máximo de sessões: 5  

---

## 📊 Resultado Esperado
- VM criada e configurada conforme requisitos.  
- Área de trabalho virtual disponível com pool de hosts.   

---

## 🧾 Entrega do Desafio
- Repositório público no GitHub com:  
  - `README.md` detalhado (este arquivo)  

---

## ✨ Autor
**Vitor [Seu Sobrenome]**  
Entusiasta de Cloud Computing  
📍 Brasília - DF  


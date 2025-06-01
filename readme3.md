# ☁️ Projeto Azure - Criação e Configuração de Máquinas Virtuais

Este projeto tem como objetivo documentar os aprendizados adquiridos durante a criação e configuração de **Máquinas Virtuais (VMs)** no **Microsoft Azure**. Abaixo está um resumo do que foi abordado:

---

## ✅ O que aprendemos

### 🔧 Criação de VMs no Microsoft Azure
Aprendemos como criar máquinas virtuais (VMs) diretamente na plataforma Azure, utilizando diferentes sistemas operacionais e tamanhos de instância, com foco em configurações eficientes e práticas recomendadas.

### 🔒 Configuração e Segurança
Durante a configuração das VMs, exploramos recursos como:
- Grupos de segurança de rede (NSGs)
- Controle de portas de entrada e saída
- Configuração de acesso via SSH ou RDP
- Gerenciamento de usuários e permissões

### 📁 Gerenciamento de Arquivos
Descobrimos como acessar e modificar os arquivos contidos dentro das VMs, seja por meio de terminal (Linux) ou área de trabalho remota (Windows), além de aplicar configurações de inicialização automática.

### ⚙️ Utilização de Configurações Pré-definidas
Utilizamos modelos prontos e imagens pré-configuradas para agilizar a criação de ambientes com:
- Software já instalado
- Configurações automatizadas
- Scripts de provisionamento

### ⚠️ Riscos de Segurança: IP Público
Identificamos que manter a **porta pública aberta** diretamente para a VM representa um risco à segurança do sistema. Práticas seguras recomendadas incluem:
- Uso de VPN ou Azure Bastion
- Restrições de IPs confiáveis
- Monitoramento constante

---

## 📌 Conclusão

A prática com a plataforma Azure mostrou como é simples e poderoso gerenciar máquinas virtuais em nuvem. Porém, aprendemos que **segurança é essencial** desde a criação da VM, e pequenos descuidos como a exposição pública desnecessária podem comprometer toda a infraestrutura.

---

## 🔗 Recursos Recomendados

- [Portal do Azure](https://portal.azure.com)
- [Documentação Microsoft Azure](https://learn.microsoft.com/azure/)
- [Melhores Práticas de Segurança no Azure](https://learn.microsoft.com/azure/security/)

---

> *Este README é parte de um exercício prático sobre computação em nuvem utilizando o Microsoft Azure.*

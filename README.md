# Sistema de Notificações em Java 📢

Projeto desenvolvido em Java com o objetivo de demonstrar o uso de **Interfaces**, **Polimorfismo** e **Orientação a Objetos**.

## 📌 Descrição

O sistema simula o envio de notificações para clientes por diferentes canais de comunicação.

Os tipos de notificação disponíveis são:

- 📧 E-mail  
- 📱 SMS  
- 💬 WhatsApp  

Cada tipo de notificação possui sua própria forma de envio, mas todos seguem a mesma interface chamada `Notificacao`.

---

## 🛠 Tecnologias utilizadas

- Java
- Programação Orientada a Objetos (POO)
- Interface
- Polimorfismo
- Scanner para entrada de dados

---

## 📂 Estrutura do projeto

- `Notificacao` → Interface principal  
- `NotificacaoEmail` → Implementação para envio por e-mail  
- `NotificacaoSms` → Implementação para envio por SMS  
- `NotificacaoWhatsApp` → Implementação para envio por WhatsApp  
- `ServicoNotificacao` → Classe responsável por executar o envio  
- `Main` → Classe principal com menu interativo  

---

## ▶ Funcionamento

Ao executar o programa, o usuário escolhe o tipo de notificação:

1 - E-mail 📧  
2 - SMS 📱  
3 - WhatsApp 💬  

Depois, digita a mensagem que deseja enviar.

Exemplo:

```bash
Escolha o tipo de notificação:
1 - E-mail
2 - SMS
3 - WhatsApp
Opção: 2

Digite a mensagem: Seu pedido foi enviado

Enviando SMS: Seu pedido foi enviado
```

---

## 🎯 Objetivo do projeto

Praticar conceitos de Programação Orientada a Objetos, especialmente:

- Criação de interfaces
- Implementação de classes
- Uso de polimorfismo
- Organização e reutilização de código

---

Desenvolvido para fins acadêmicos 🚀

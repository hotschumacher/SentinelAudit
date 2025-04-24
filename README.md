# 🛡️ SentinelAudit | [![GitHub Stars](https://img.shields.io/github/stars/hotschumacher/SentinelAudit?style=social)](https://github.com/hotschumacher/SentinelAudit/stargazers)

> **"O Wireshark dos Logs Windows"**  
> Monitoramento resiliente de segurança e ferramenta forense para ambientes Windows + Zabbix.  
> **Destaque-se em incidentes críticos: ransomware, escalonamento de privilégios e acessos não autorizados.**

---

## 🔥 **Por que contribuir?**
- **Projeto técnico desafiador** com aplicação real em segurança cibernética.  
- **Open-source puro**: Sem "versão premium", sem vendas ocultas – apenas código que resolve problemas.  
- **Seu nome no hall da fama**: Reconhecimento como especialista em logs Windows e forense.  

*(Queremos pessoas que pensem em **"como eu detectaria um ataque se estivesse no lugar do hacker?"**)*  

---

## 🛠️ **Tecnologias-Chave**
| Área               | Stack                          |
|--------------------|--------------------------------|
| **Coleta de Logs** | Python + Win32 API / C# (.NET) |
| **Armazenamento**  | SQLite (local) + Zabbix        |
| **Segurança**      | Criptografia AES (arquivos)    |
| **Análise**        | YARA rules (detecção de padrões) |

---

## � **Como Você Pode Ajudar?**
### 👨‍💻 **Para Devs**
- **Implementar novos EventIDs críticos** (ex.: [EventID 4698](https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/event.aspx?eventID=4698) - Criação de tarefas agendadas).  
- **Criar módulos de detecção**:  
  - Ransomware (alteração em massa de arquivos).  
  - Persistência (registro Run Keys, serviços não autorizados).  

### 🔍 **Para Analistas de Segurança**  
- **Propor cenários de ataque** para testar a ferramenta.  
- **Melhorar regras de detecção** (ex.: "Como identificar Pass-the-Hash?").  

### 📚 **Para Documentadores**  
- **Escrever guias forenses**: "Como usar o SentinelAudit para investigar um incidente X?"  

---

## 🚀 **Primeiros Passos para Contribuir**
1. **Clone o repositório**:  
   ```bash
   git clone https://github.com/hotschumacher/SentinelAudit.git


Instale as dependências (Python):
Pip install -r requirements.txt
Escolha uma issue marcada como good first issue ou proponha uma nova funcionalidade.

📌 Regras do Jogo
Seu nome estará no CHANGELOG.md para toda contribuição relevante.

Discussões técnicas > Hierarquia: Melhor argumento ganha, não importa quem seja.
Sem ego: Se você encontrar um bug, ganha um 🍪 virtual (e créditos no relatório).

📬 Quem Está Por Trás?
Fernando Hotschumacher (@hotschumacher) - Idealizador e mantenedor.

Lista de colaboradores: CONTRIBUTORS.md (adicione seu nome aqui!)

"Não queremos ser mais um SIEM genérico. Queremos ser a ferramenta que você usaria para investigar seu próprio ataque."

🔹 Licença: MIT - Faça bom uso, mas mantenha os créditos.
🔹 Não é um projeto comercial - É um projeto de especialistas, para especialistas.
   

# Situação de Aprendizagem Somativa (SAS) - Automação de Serviços Linux

Esta é uma **Situação de Aprendizagem Somativa** que visa avaliar as competências dos alunos na criação de scripts em Bash para automação de serviços em sistemas Linux. Os alunos devem desenvolver os scripts conforme os enunciados específicos listados abaixo, entregá-los em um repositório público no GitHub e realizar uma apresentação em sala de aula na data determinada pelo instrutor.

**Instruções Gerais:**
- Cada trabalho corresponde a um serviço Linux específico.
- O script principal de cada serviço deve seguir o padrão `<funcionalidade>_<serviço>.sh` (ex.: `webserver_apache.sh`).
- Os scripts secundários devem ser nomeados de forma lógica e consistente pelo aluno.
- Os scripts devem ser autônomos, sem interação com humanos, recebendo valores via parâmetros.
- Entrega: repositório público no GitHub com todos os scripts e um README explicativo.
- Apresentação: os alunos devem demonstrar o funcionamento dos scripts em sala na data estipulada.

---

## SAS-01: Automação de Serviços Linux - Apache (Samuel e Pedro Neres)

**Enunciado:**  
Desenvolva um conjunto de scripts em Bash para automatizar a administração do serviço Apache. O script principal deve ser chamado `webserver_apache.sh`. Cada funcionalidade deve ser implementada em um script independente. Caso identifique opções adicionais relevantes, inclua-as como scripts extras.

**Opções do Menu:**
- 1. Iniciar / Parar / Reiniciar  
   - 1.1. Iniciar  
   - 1.2. Parar  
   - 1.3. Reiniciar  
- 2. Configurar virtual hosts  
   - 2.1. Adicionar virtual host  
   - 2.2. Remover virtual host  
- 3. Ativar/Desativar módulos  
   - 3.1. Ativar módulo  
   - 3.2. Desativar módulo  
- 4. Verificar logs  
   - 4.1. Exibir log de erros  
   - 4.2. Exibir log de acesso  

**Requisitos:**  
- O script principal (`webserver_apache.sh`) deve chamar os scripts específicos conforme os parâmetros recebidos.  
- Cada script deve ser autônomo e executar sua tarefa sem prompts interativos.  
- Os scripts devem receber parâmetros para operar.  
- Adicione scripts extras, se necessário, com nomes definidos pelo aluno.

---

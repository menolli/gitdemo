# Histórias de Usuários — Cadastro de Alunos

## Contexto
Cadastro de alunos no sistema de biblioteca para permitir empréstimo, devolução e gestão de usuários.

## Histórias

### HU01 — Cadastro básico de aluno
Como atendente da biblioteca,  
quero cadastrar um aluno com seus dados principais,  
para que ele possa utilizar os serviços da biblioteca.

**Critérios de aceitação:**
- Deve ser possível informar nome completo, matrícula, curso, e-mail e telefone.
- O sistema deve indicar campos obrigatórios não preenchidos.
- Ao salvar com sucesso, o aluno deve ficar disponível para consulta.

### HU02 — Validação de matrícula única
Como atendente da biblioteca,  
quero que a matrícula do aluno seja única no sistema,  
para evitar cadastros duplicados.

**Critérios de aceitação:**
- Não deve ser permitido cadastrar dois alunos com a mesma matrícula.
- O sistema deve exibir mensagem clara quando a matrícula já existir.

### HU03 — Consulta de aluno cadastrado
Como atendente da biblioteca,  
quero pesquisar alunos cadastrados,  
para localizar rapidamente o cadastro antes de um empréstimo.

**Critérios de aceitação:**
- Deve ser possível buscar por nome ou matrícula.
- O resultado deve listar os dados básicos do aluno encontrado.

### HU04 — Atualização de cadastro
Como atendente da biblioteca,  
quero editar os dados de um aluno,  
para manter as informações atualizadas.

**Critérios de aceitação:**
- Deve ser possível alterar e-mail, telefone e curso.
- As alterações devem ser salvas e refletidas em consultas futuras.

### HU05 — Inativação de aluno
Como bibliotecário,  
quero inativar alunos que não devem mais utilizar o sistema,  
para controlar o acesso aos serviços da biblioteca.

**Critérios de aceitação:**
- O status do aluno deve poder ser alterado para inativo.
- Alunos inativos não devem realizar novos empréstimos.

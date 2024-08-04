# User Story: Cadastro de novos cursos.
Como uma instituição quero cadastrar um novo curso no site
#

## Cenários - Cadastro de cursos
##

### CT 001: Cadastro de um novo curso online

##### **Given** Acesso o site e clico em cadastrar curso.
##### **And** Preencho todos os campos com as informações do curso
##### **And** No campo “Tipo de curso” seleciono a opção “Online”
##### **When** Clico em “Cadastrar Curso”
##### **Then** O curso será cadastrado e aparecerá na lista;

### CT 002: Cadastro de um novo curso presencial

##### **Given** Acesso o site e clico em cadastrar curso
##### **And** Preencho todos os campos com as informações do curso
##### **And** No campo “Tipo de curso” seleciono a opção “Presencial”
##### **When** Clico em “Cadastrar Curso”
##### **Then** O curso será cadastrado e aparecerá na lista;

### CT 003: Cadastro de curso com data inválida.

##### **Given** Acesso o site e clico em cadastrar curso.
##### **And** Preencho todos os campos com as informações do curso
##### **And** No campo "Data de início" e "Data de fim" preencho com uma data inválida
##### **When** Clico em “Cadastrar Curso”
##### **Then** O site apresenta uma mensagem informando que as datas estão incorretas;

# User Story: Listar Cursos
Como usuário do site quero encontrar um curso ao qual atenda minhas necessidades.

## Cenários - Listar cursos

### CT 004: Listar cursos existentes
##### **Given** Acesso o site
##### **And** Clico em "Listar Cursos"
##### **Then** Todos os cursos cadastrados no site serão apresentados na tela;

# User Story: Excluir curso
Como instituição que já tenha cursos cadastrados na plataforma, desejo remover um curso que não aceita mais inscrições.

## Cenários - Excluir cursos

### CT 005: Excluir curso
##### **Given** Acesso o site
##### **And** Clico em "Listar Cursos"
##### **And** Todos os cursos cadastrados no site serão apresentados na tela;
##### **And** Clico em "Excluir curso"
##### **Then** O site apresenta uma mensagem e o curso será excluído;

## Notas

- Campos obrigatórios incluem: Nome do Curso, Descrição,Instrutor, URL da imagem de capa, Data de Início, Data de Término, Número de vagas, Tipo de curso, Endereço ou Link de inscrição.
- A validação de dados deve ser realizada tanto no lado do cliente quanto no lado do servidor para garantir a integridade dos dados.
- A lista de cursos deve ser atualizada em tempo real após a adição ou a exclusão de um novo curso.

## Evidências
https://drive.google.com/drive/u/1/folders/1DKma6KRiRuWOuyvi6VKscjKbX5dfKr94

## Planilha com casos de teste, passo a passo, cenários e user story
https://docs.google.com/spreadsheets/d/1OmszAVo1IDj8wUqpnaXyAdBQO0ELkLDyEpCH37q4ffA/edit?usp=sharing

## Planilha com relatório de erros encontrados
https://docs.google.com/spreadsheets/d/1BHr404D7k1UK0oqIR60xTaDhZhEmAgmlJmwqTDMUD-E/edit?usp=sharing


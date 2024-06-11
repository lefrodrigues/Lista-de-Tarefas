# Lista-de-Tarefas

 Uma aplicação frontend com HTML, CSS e JS puro para gerir tarefas. No backend vamos ter uma API NodeJS + Express + MySql para servir o frontend.

# BASE DE DADOS

    users
        id
        username
        password
        created_at
        updated_at

    tasks
        id
        id_user
        task_text
        task_status(nova | em progresso | cancelada | concluída)
        created_at
        updated_at


# TAREFAS DESENVOLVIDAS NO PROJETO

    > criar a estrutura inicial
        - base do frontend (html css js | bootstrap)
        - base do backend (node + express + mysql) com uma resposta padrão

    > no frontend
        - páginas necessárias para a navegação na aplicação
        - testes de comunicação entre front e backend - utilização de Ajax (XMLhttprequest | fetch API)

    
    
    
    - estrutura base de cada
        bootstrap (slate) bootswatch
        fontawesome

    
    - ver tarefas
        título
        filtro para escolher tarefas que queremos ver (select)
        botão para adicionar tarefas 
        (mensagem caso não haja tarefas)
        caixa para tarefas
            - possibilidade de alterar o status, editar, e eliminar tarefas, contador de tarefas

    - adicionar tarefa
        input:text com o texto da tarefa 
        botão para cancelar e submeter tarefa

    - editar tarefa
        input:text para editar o texto da tarefa
        botão para cancelar e submeter a alteração

    Deletar será feito com modal    

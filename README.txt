A atividade foi feita usando a linguagem Java, com interface gráfica pelo Swing, através da Eclipse IDE 2020-06.

1 - Para compilar, o projeto deve ser importado no eclipse, e então o driver do PostgreSQL deve ser referenciado no projeto clicando com botão direito no nome, e acessando o caminho Build Path -> Add External Archives, assim o driver deve ser selecionado na pasta em que se encontra e o procedimento deve ser concluído.

2- O banco de dados utilizado foi o PostgreSQL 13. Os comandos em SQL para criação do banco estão no arquivo "Instruções para Criação de Banco de Dados.txt"

3 - Para o funcionamento correto do programa, o arquivo "DataBase.java" deve ser alterado para adequar as informações de conexão ao banco de dados que estiver sendo utilizado, por padrão está definido da seguinte forma:

String stringDeConexao = "jdbc:postgresql://localhost:5432/estoque";
	String usuario = "postgres";
	String senha = "postgres";

4- O driver se chama "postgresql-42.2.8.jar" e se encontra na pasta junto aos arquivos de texto.

5- O arquivo a ser compilado pelo eclipse para dar início a execução do programa é o "MainWindow.java" que se encontra no pacote "ui".

6- O arquivo executável, que está na pasta junto aos arquivos de texto, estará usando as configurações padrão de conexão ao banco. Portanto, se houver alteração, o arquivo executável deve ser gerado novamente para o funcionamento correto do programa.
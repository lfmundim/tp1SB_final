#Sobre o makefile:
	-> Para compilar o programa, utilize o comando 'make'. Para limpar todos os arquivos criados (inclusive o executável, necessitando nova compilação), utilize o comando 'make clean'.	
	-> Há funções prontas para executar os arquivos teste inclusos: 'make run1' e 'make run2', que utilizam (respectivamente) 'tst/entrada1.a' e 'tst/entrada2.a'.

#Sobre a execução do programa:
	-> Para execução do programa, utiliza-se a seguinte chamada: './tp1 arquivo', caso tenha sido compilado com o comando 'make' especificado acima. O nome do arquivo a ser montado deve ser colocado no lugar do argumento 'arquivo' (argv[1]).
	-> A saída do programa é impressa em um arquivo no formato 'mif' chamado 'saida.mif'. Cada vez que o programa é executado, esse arquivo é substituído. Esse arquivo também é deletado pelo comando 'make clean'.

#Arquivos extras:
	-> Escolheu-se incluir no arquivo compactado o código para a 'Swombat.cpu', para caso o usuário não o possua.
	-> Incluiu-se, na pasta 'doc', as imagens utilizadas na documentação para melhor visualização, bem como as imagens referenciadas por ela.
	-> Por último, foi incluído o PDF com a especificação do trabalho prático.

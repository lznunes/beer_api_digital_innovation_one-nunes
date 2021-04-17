https://github.com/rpeleias/beer_api_digital_innovation_one

ERRO: Ao executar comando "mvn -clean test" apresentou mensagem: "Invalid Target Release: 14"
SOLUCAO: Executar o comando "mvn -version"
		 Anotar a versão do Java exibida
		 Editar o arquivo porn.xml e colocar a mesma versão nas tags "<source>" e "<target>"
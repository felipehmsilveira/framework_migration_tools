===================================================
#PRÉ CONFIGURAÇÃO

sudo apt-get update

sudo apt-get install default-jre

sudo apt-get install default-jdk

git clone https://github.com/felipehmsilveira/framework_migration_tools.git

===================================================
#Execução

createBuildProperties {
	::Salvar suas credenciais
}

createRetrieve {
	::Configurar seu retrieve e criar o arquivo bash para o executar o retrieve e o deploy
}

remove {
	refazer todas mudanças (apaga os diretórios criado)
}
===================================================



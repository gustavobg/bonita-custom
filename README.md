bonita-custom
=============

Para instalar copie os conteúdos dos seguintes diretórios para o respectivo caminho na sua máquina local (Substitua todos os arquivos)

** DICAS IMPORTANTES *** 
1) Antes de colar os arquivos faça um backup dos arquivos originais, assim não é necessário remover e reinstalar o BONITA para voltar para as configurações originais.

2) Cuidado com o cache, após substituir os arquivos limpe o cache do navegador. (Se persistir, utilize alterne para outro navegador para verficar, Firefox / Chrome)

-------------------
** PROCEDIMENTO **

Copie os arquivos contidos nos seguintes diretórios para seu destino:

1)	Origem: workspace-tomcat-bonita-client-platform-tenant-template-work-lf-default 
	Destino: C:\BonitaBPMCommunity-6.0.0\workspace\tomcat\bonita\client\platform\tenant-template\work\looknfeel\default

2)	Origem: workspace-tomcat-webapps-bonita-console-css
	Destino: C:\BonitaBPMCommunity-6.0.0\workspace\tomcat\webapps\bonita\console\css

3)	Origem: workspace-tomcat-webapps-bonita-console-css-skins-default-images
	Destino: C:\BonitaBPMCommunity-6.0.0\workspace\tomcat\webapps\bonita\console\css\skins\default\images

IMPORTANTE: Para verificar as alterações, pode ser necessários fechar o bonita e abrir novamente.

-------------------------------
** LIMITAÇÃO NA APRESENTAÇÃO **

-- Ao finalizar um processo na USERXP, irá aparecer a seguinte mensagem: 
		A task is now available
		      Tarefa XYZ
para fins de apresentação, não clique neste link que aparece, ao invés disso, clique na caixa de entrada e continue o processo por lá. Por alguma razão que ainda não descobri, ao usar o link que aparece, o título da tarefa não é atualizado corretamente. (Apesar do processo ser continuado sem problemas)

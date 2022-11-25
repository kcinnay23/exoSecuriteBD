# Exercice 1 : Les types d'attaques contre les bases de données 
Les types d'attaques:  
Mauvaise presse de l'information;  
Modification des données incorrectes  
Déni de service  
Ces 3 catégories portent plus atteintesà la confidentialité, l'intégrité.  
Les SGBD commerciaux actuels sont faibles, exposés à des attaques simples. Parmi ceux-ci: chevaux de Troie, Inference, ver, Tracker (comploteurs), Trapdoor (échappatoires).  
Les 10 principales menaces de sécurité des bases de données:
1. Abus de privilège excessif
2. Abus de privilège légitime
3. Elévation de privilège
4. Exploitation de failles des bases de données vulnérables ou mal configurées 
5. Injection SQL
6. Faiblesse de l’audit natif
7. Déni de service
8. Vulnérabilités des protocoles de communication des bases de données
9. Copies non autorisées de données sensibles 
10. Exposition de données de sauvegarde

# Exercice 2 : Emplacement des fichiers de stockage selon les SGBD
Oracle:

Chaque instance du service de données HA pour Oracle Database conserve des fichiers journaux dans des sous-répertoires du répertoire /var/opt/SUNWscor.

Le répertoire /var/opt/SUNWscor/oracle_server contient les fichiers journaux du serveur Oracle Database.

Le répertoire /var/opt/SUNWscor/oracle_listener contient les fichiers journaux du listener Oracle Database.

Le répertoire /var/opt/SUNWscor/oracle_asm contient le fichier journal d'Oracle ASM.

MySQLServer:

Summary.txt	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log

Summary_<Nom_machine>_Date.txt	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log\YYYYMMDD_hhmmss

Detail.txt	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log\YYYYMMDD_hhmmss

Magasins de données	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log\YYYYMMDD_hhmmss\Datastore

Fichiers journaux MSI	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log\YYYYMMDD_hhmmss\<Nom>.log

ConfigurationFile.ini	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log\YYYYMMDD_hhmmss

SystemConfigurationCheck_Report.htm	%programfiles%\Microsoft SQL Server\nnn\Setup Bootstrap\Log\YYYYMMDD_hhmmss

Pour des installations sans assistance	%temp%\sqlsetup*.log

PostresQL:

MySQl:
C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm

C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd 


# Exercice 3 : Politique de sécurité selon (isecure)

# Exercice 4 : Nom du package qui permet de limiter les droits du DBA Oracle
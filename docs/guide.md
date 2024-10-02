Trabalho 1 - myPod

- Todas as issues criadas têm suas descrições documentadas.
- As versões são entregues semanalmente, visto que as atualizações de imagens ficam disponíveis com prazo de uma semana.
- Os branches de versão foram criados pelo próprio paindel de comando.
- A correção emergencial não alterou a versão. A alteração foi feita no branch de bugs, enviado para a main via PR e posteriormente feito merge para a versão do cliente, para garantir o processo e a qualidade. 

Atividades para o desenvolvimento:


1. Criado novo repositório trabalhoum
2. Conectado no novo repositório: git remote add origin http://github.com/gabrielabonella/trabalhoum
3. Git branch develop
4. Git push -u origin develop
5. Git branch funcionalidadeA
6. Git push -u origin funcionalidadeA
7. Git branch BugA
8. Git push -u origin BugA
9. Git branch BugB
10. Git push -u origin BugB
11. Download do projeto do professor code2
12. Incluído na pasta local
13. Na branch develop, git add . e git commit -m “primeira carga”
14. Push no branch develop
15. Git checkout main - para ir para o branch main
16. Git merge develop para levar todos os arquivos originais do develop para a main 

Commits/Liberações:

17. Commits de acordo com cada Issue
18. Criada uma branch preDevelop para nao afetar ainda a develop
19. Criada Pull Request Issue bugA-1234 para a preDevelop
20. Criada Pull Request bugB-1235 para a preDevelop
21. Criada Pull Request funcionalidadeA-1237 para a preDevelop
22. Alterada a branch para bugA
23. Git pull na bugA
24. Alteração do fonte conforme issue bugB-1238 (com erro para solicitar revisão de código)
25. Criada Pull Request bugB para a preDevelop com a revisao do bot011024
26. Revisão do bot na PR: Changes requested pelo bot011024
27. Commit realizado no arquivo e solicitado para revisar
28. PR aprovada pelo bot011024
29. Criada a PR bugB para a preDevelop que foi revisada
30. Commit da issue bugA-1236
31. Merge através de PR na preDevelop
32. PR para merge da develop para a main
33. Criada a branch da versão/release V2024.10.1
34. Correção emergencial: bugA-1240, depois PR para a main e depois para a versao. A correção passou pela main para que faça um pull nas outras branchs.

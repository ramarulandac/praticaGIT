11. git reset --hard HEAD~ Devuelve el grafo al commit anterior dejando vacío el working copy
12. git reset --hard HEAD@{1} Es la entrada del reflog donde se encuentra el commit del grafo anterior. Ya que no está en git log de la rama.  
13. No. No hay ningún cambio en Master que pueda tener conflicto con el último commit de styled.
19. Sí. Git no sabe cómo mezclar las frases de la oración a git.
21. No. Es un merge fast-forward.
25. git log --graph.
26. No podrá ser ff. Se necesita un nuevo commit para conservar los anteriores.
27. git reset HEAD~
28. git checkout git-nuestro.md
29. git branch -D title
30. git reflog -- ver el log general
    git checkout 784a08e -- recuperar el commit
    git branch title -- Crear la rama
    git checkout title -- Revisar que está todo

32. Dos veces:
    git reset --hard HEAD~1
    git reset --hard HEAD~1

33.
   git reflog
   git checkout 8b12dd4
   git branch styled

   git reflog
   git checkout 1f466b6
   git branch htmlify

   git checkout style
   git reset --hard 98774f1 --> Merge style absorve a htmlify

   git checkout master
   git reset --hard 98774f1

   git checkout 784a08e
   git branch title 



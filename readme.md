#Ejercicio 1

##Preguntas

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**

```git reset --hard HEAD~1```

> El comando que permite deshacer el último commit es *"git reset HEAD~1"*. Añadiendo el modificador --hard, nos aseguramos de borrar los cambios realizados en el working copy. 

<br />
**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

```git reflog```<br />
```git reset --hard a7cfce4```

> Primero utilizo *"git reflog"* para ver cual era el HASH del commit anterior al que estoy ahora, y a continuación vuelvo a ese commit haciendo un *"git reset --hard"* para asegurarme que el working copy tiene la misma versión que el repositorio.

<br />
**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

> No causa ningún conflicto, puesto que al absorber a una rama que ya estaba contenido en el propia rama *styled*, no se produce ningún cambio.

<br />
**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

> Sí causa un conflicto. El contenido del archivo *git-nuestro.md* es distinto (en líneas coincidentes), y ninguna de las ramas estaba contenido en la otra, por lo que no era posible un *merge fast forward*.

<br />
**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

> No causa ningún conflicto. La rama *master* está contenida dentro de la rama *styled*, por lo que es posible hacer el *merge fast forward* sin problemas.

<br />
**¿Qué comando o comandos utilizaste en el paso 25?**

```git  log --graph --decorate --pretty=oneline```

<br />
**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

> Sí podría ser fast forward, puesto que la rama *title* contiene a la rama *master* (forman una lista).

<br />
**¿Qué comando o comandos utilizaste en el paso 27?**

```git reset HEAD~1```

<br />
**¿Qué comando o comandos utilizaste en el paso 28?**

```git checkout -- git-nuestro.md ```

<br />
**¿Qué comando o comandos utilizaste en el paso 29?**

```git branch -D title```

<br />
**¿Qué comando o comandos utilizaste en el paso 30?**

```git reflog```<br />
```git checkout 164732a```

<br />
**¿Qué comando o comandos usaste en el paso 32?**

```git ```

<br />
**¿Qué comando o comandos usaste en el punto 33?**

```git ```


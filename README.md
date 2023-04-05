## Pour merge correctement :

1. Sur ta branche:

```
git add .
git commit -m" "
git push

Garder le nom de sa branch de côté
```

2. Aller sur develop

```
 git checkout develop
```

3. Se mettre à jour de develop

```
git pull develop
```

4. Retourner sur sa branche

```
git checkout NOM_DE_LA_BRANCHE
```

5. Fusionner les infos de develop et de ta branche

```
git merge develop
```

6. Résoudre les conflits
   ![Hasbu](https://lasueur.com/wp-content/uploads/2022/09/hasbulla-UFC.jpg)
7. Une fois les conflits résolu

```
git add .

git commit -m "conflicts solved"
```

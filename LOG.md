# Log

This is a random log/blog of what I'm doing while I run this project.

## Sep 21, 2023, 2:48 AM GMT-3
Vine tarde de salir la noche del miércoles. Hoy, como podrá comprobarse por la fecha, ya es Jueves.

Abrí youtube.com y me recomendó (entre otras cosas, pero en primer lugar) esto:

https://www.youtube.com/watch?v=rdl5dL34V5s

Título del video: "VILLARRUEL CONTRA TODOS LOS ZURDOS EN 🔴 EL DEBATE DE VICES EN VIVO 🔴"

El canal se llama "Javier Milei" (URL: https://www.youtube.com/@JavierMileiOK).

No soy Mileista así que escribo esto anecdóticamente. Para dejar registro. Porque se me ocurrió que podía estar presente en este repo.

Pero antes de esa idea, me dije a mí mismo: "tendría que escribir en el README.md/LEEME.md" qué es lo que estoy intentando hacer con este proyecto.

Escribir sobre la Neutralidad de la Información (o al menos su intención), etc.

Dudo que alguien lea algún día TODO esto que escribo pero aún así, me lo tomo con Responsabilidad.

Nunca Se Sabe.

Dicho Esto, Procedo a Actualizar\
El Proyecto.

## Sep 18, 2023, 2:18 PM GMT-3

Mientras hago esto vocalizo. Es Lunes, 18 de Septiembre 13:58 P.M. Pensar que tenemos dos sistemas de Horas distintos (o habrá más? [TO-DO: averigüar la historia de los sistemas de Horas]) en El Mundo.

Escribo y La Vocalización, Es Cualquier Cosa.

Voy a Hacer, Una Cosa A La Vez, Y Bien.

Lo Mejor Que Pueda,

Siempre.

---

YouTube FullScreen, para concentrarse.

---

Son las 14:14. Vocalicé un toque, me salió más o menos. Mientras tanto esperaba que https://github.com/marcelomazza/politica-argentina el Push que hice recién:

Log:

```
~/psl/politica-argentina $ echo "# politica-argentina" >> README.md
~/psl/politica-argentina $ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: 	git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: 	git branch -m <name>
Initialized empty Git repository in /Users/marcelo/psl/politica-argentina/.git/
~/psl/politica-argentina (master #) $ git add README.md
~/psl/politica-argentina (master +) $ git commit -m "first commit"
[master (root-commit) 9839e9b] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
~/psl/politica-argentina (master) $ git branch -M main
~/psl/politica-argentina (main) $ git remote add origin git@github.com:marcelomazza/politica-argentina.git
~/psl/politica-argentina (main) $ git push -u origin main
~/psl/politica-argentina (main) $ s
On branch main
nothing to commit, working tree clean
~/psl/politica-argentina (main) $ s
On branch main
nothing to commit, working tree clean
~/psl/politica-argentina (main) $ s
On branch main
nothing to commit, working tree clean
~/psl/politica-argentina (main) $ git remote -v
origin	git@github.com:marcelomazza/politica-argentina.git (fetch)
origin	git@github.com:marcelomazza/politica-argentina.git (push)
~/psl/politica-argentina (main) $ s
On branch main
nothing to commit, working tree clean
~/psl/politica-argentina (main) $ s
On branch main
nothing to commit, working tree clean
~/psl/politica-argentina (main) $ ls
README.md
~/psl/politica-argentina (main) $ touch LEEME.md
~/psl/politica-argentina (main) $ subl LEE
The file /Users/marcelo/psl/politica-argentina/LEE does not exist.
~/psl/politica-argentina (main) $ subl LEEME.md
~/psl/politica-argentina (main) $
```

---

Voy a pushear esto, así como está, a ver qué pasa.

---

Ahí pusheó, había un error que no me había salido antes:

```
~/psl/politica-argentina (main +) $ git commit -m "Agrego LEEME.md y duplico en README.md, así nomás, borrador"
[main a3b3e65] Agrego LEEME.md y duplico en README.md, así nomás, borrador
 2 files changed, 148 insertions(+), 1 deletion(-)
 create mode 100644 LEEME.md
 rewrite README.md (100%)
~/psl/politica-argentina (main) $ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

~/psl/politica-argentina (main) $ git push -u origin main
Warning: Permanently added the RSA host key for IP address '140.82.114.4' to the list of known hosts.
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 1.55 KiB | 1.55 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:marcelomazza/politica-argentina.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
~/psl/politica-argentina (main) $
```

Listo, genial.
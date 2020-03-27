<h1>First Partial Exam</h1>
<h2>Manuel Torres Magdaleno</h2>


<p><p>PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git clone https://github.com/manueleduar/First-Partial-Exam-1.git                                                                                           Cloning into 'First-Partial-Exam-1'...
remote: Enumerating objects: 16, done.
remote: Counting objects: 100% (16/16), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 16 (delta 0), reused 16 (delta 0), pack-reused 0
Unpacking objects: 100% (16/16), done.
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git status                          On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        deleted:    ../../README.md
        deleted:    ../../index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        ../../Clase/
        First-Partial-Exam-1/
        ../../Laboratorio/

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git add .                           warning: adding embedded git repository: Examenes/Parcial 1/First-Partial-Exam-1
hint: You've added another git repository inside your current repository.
hint: Clones of the outer repository will not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> Examenes/Parcial 1/First-Partial-Exam-1
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached Examenes/Parcial 1/First-Partial-Exam-1
hint:
hint: See "git help submodule" for more information.
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git status                          On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   First-Partial-Exam-1

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)

        modified:   First-Partial-Exam-1 (untracked content)
        deleted:    README.md
        deleted:    ../../README.md
        deleted:    ../../index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        ../../Clase/
        ../../Laboratorio/

PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git add .                           PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git status                          On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   First-Partial-Exam-1
        deleted:    README.md

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
  (commit or discard the untracked or modified content in submodules)

        modified:   First-Partial-Exam-1 (untracked content)
        deleted:    ../../README.md
        deleted:    ../../index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        ../../Clase/
        ../../Laboratorio/

PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git reset                           Unstaged changes after reset:
D       Examenes/Parcial 1/README.md
D       README.md
D       index.html
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git status                          On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        deleted:    README.md
        deleted:    ../../README.md
        deleted:    ../../index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        ../../Clase/
        First-Partial-Exam-1/
        ../../Laboratorio/

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git checkout                        D       Examenes/Parcial 1/README.md
D       README.md
D       index.html
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git push                            Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (5/5), 471 bytes | 235.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
remote: This repository moved. Please use the new location:
remote:   https://github.com/manueleduar/Laboratorio_claseWeb_1.git
To https://github.com/manueleduar/Laboratorio_claseWeb.git
   5c78c12..763f8f4  master -> master
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1> git status                          On branch master
Your branch is up to date with 'origin/master'.


PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.md

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git add .
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git commit -m "READMEMODIFIED"
[master 3e54f22] READMEMODIFIED
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 339 bytes | 339.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/manueleduar/First-Partial-Exam-1.git
   3f28b68..3e54f22  master -> master
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1>

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git add .
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git commit -m "README added"
[master 7db9005] README added
 1 file changed, 161 insertions(+), 1 deletion(-)
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1> git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.60 KiB | 545.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/manueleduar/First-Partial-Exam-1.git
   3e54f22..7db9005  master -> master
PS C:\Users\Manuel\Documents\Tec\Desarrollo de Aplicaciones Web\Examenes\Parcial 1\First-Partial-Exam-1></p></p>
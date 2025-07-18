# git-cafe-exercise
##### Bundle 5 Exercise 2

``` bash

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git clone https://github.com/samuel-ishimwe203/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects: 100% (107/107), 1.95 MiB | 105.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.
            

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ cd 'c:\Users\user\Desktop\My folder\Gym-Git-Exercises\git-cafe-exercise'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (main)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (main)
$ git commit -m"new changes to index"
[main 330e141] new changes to index
 1 file changed, 1 insertion(+), 1 deletion(-)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/samuel-ishimwe203/git-cafe-exercise.git
   d1d3f9c..330e141  main -> main

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (main)
$

```


###### Bundle 6 Exercise 1

```bash

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (main)
$ git checkout -b ft/cafe1
Switched to a new branch 'ft/cafe1'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (ft/cafe1)
$ touch menu.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (ft/cafe1)
$ git add menu.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (ft/cafe1)
$ git commit -m"menu page updated"
[ft/cafe1 700013e] menu page updated
 1 file changed, 12 insertions(+)
 create mode 100644 menu.html


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises/git-cafe-exercise (ft/cafe1)
$ git push  origin ft/cafe1
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 441 bytes | 441.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/cafe1' on GitHub by visiting:
remote:      https://github.com/samuel-ishimwe203/git-cafe-exercise/pull/new/ft/cafe1
remote:
To https://github.com/samuel-ishimwe203/git-cafe-exercise.git
 * [new branch]      ft/cafe1 -> ft/cafe1
      
```


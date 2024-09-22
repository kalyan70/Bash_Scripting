| COMMAND | DESC |
| -------- | -------- |
| `.` | current directory |
| `..` | parent direcotry |
| `-name` | search with name |
| `-iname` | **case sensitive** |
| `-type f` | **dispalys only files** |
| `-type d` | **displays only dir's** |
| `find . -name sum.sh` | current directory sum.sh unda leda |


| COMMAND | DESC | OUTPUT |
| -------- | -------- | -------- |
| `find . -name sum.sh` | current directory sum.sh unda leda | ./sum
| `find . -name *.sh` or `find . -name "*.sh"` "| if you want print only .sh files | ./home/c/kal.sh , ./home/c/mal.sh|
| `-iname`| ignores case sensitive  | see below |
| `find . -name game`| nrml print | ./game |
| `find . -iname game`| it will ignore case senstive | ./game , ./Game |
| `-type f`| print all file types  | see below |
| `find . -type f`| it displays only files | all files under present dir  |
| `find . -type d`| it displays only files | all dir's under present dir |
| `-mtime`| last modified file  | see below |
| `find . -mtime -7`| last 7 days after create ayina files | aa,bb,cc |
| `find . -mtime +7`| last 7 days before create ayina files | ss,abc.txt |
| `find . -mtime 7`| exact 7th day | game |



| COMMAND | DESC |
| -------- | -------- |
| `find . -empty`| to check empty files & directories|
| `find . -empty -type f`| only empty files|
| `find . -not`| (not empty files)|
| `find . -perm 777`| current directory 777 permission tho unna direcotires print chestadi|
| `find . -mmin -60`| 60 min kanna takkuva lopu create chesina files|


# THE_KALYAN_KANDA'S_NOTES



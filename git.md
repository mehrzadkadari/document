# Git

1. **creat repository localhost**
   
   ```shell
   git init
   ```
   
   ---

2. **status stage**
   
   ```bash
   git status
   ```
   
   ---

3. **add stage**
   
   ```bash
   git add test.file
   ```
   
   ---

4. **Description for project**
   
   ```bash
   git comit -m "description"
   ```
   
   ---

5. **show modified**
   
   ```bash
   git diff
   ```
   
   ---

6. **show comit inline**
   
   ```bash
   git log --oneline    
   ```
   
   * **how comit inline tow lost line**
     
     ```bash
     git log -2 --oneline
     ```
     
     ---

7. **returen config**
   
   ```bash
   git checkout -- name-file
   ```
   
    ---

8. **unstage(returen config to unstage)**
   
   ```bash
   git reset name-file
   ```
   
   ---

9. **reset hard and software comit**
   
   ```bash
   git reset --hard id-comit
   git reset id-comit
   ```
   
   ---

10. **create branch**
    
    ```bash
    git branch name-branch
    or
    git checkout -b name-branch
    ```
    
    ---

11. **move betwean branch**
    
    ```bash
    git checkout name-branch
    ```
    
    ---

12. **delete branch**   
    
    ```bash
    git branch -d name-branch
    ```
    
    ---    

13. **show project graph**        
    
    ```bash
    git log --graph
    ```
    
    ---

14. **merg brnach together**
    
    ```bash
        git merg name-branch
    ```
    
    ---

15. **git stash for save modify in branch**
    
    ```bash
    git stash
    ```
    
    ---

16. **list stash**
    
    ```bash
    git stash list
    ```
    
    ---

17. **delete stash**
    
    ```bash
    git stash drop name-stash
    ```
    
    ---

18. **git stash apply**
    
    ```bash
    git stash apply name-stash
    ```
    
    ---

19. **ignore file to show add stage**
    
    ```
    make file name of .gitignore
    ```
    
    ![](C:\Users\joker\Desktop\Captursdade.PNG)
    
    ---

20. **git add remote**
    
    ```bash
    git remote add origin name-repository
    ```

21. **show remote repository**
    
    ```bash
    git remote
    ```

22. **push project to gihub repository**
    
    ```bash
    git push -u origin name-branch
    ```

23. **pull project of repository**
    
    ```bash
    git pull origin
    ```

24. **clone project of github**
    
    ```bash
    git clone url-github-project name-save
    ```

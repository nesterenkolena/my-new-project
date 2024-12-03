   mkdir my-new-project
   cd my-new-project
      git init
      echo "# My New Project" >> README.md
         git add README.md
   git commit -m "Initial commit"
      git remote add origin https://github.com/nesterenkolena/1.git
      git push -u origin master
      cd ..
   rm -rf my-new-project
      git clone https://github.com/nesterenkolena/my-new-project.git
   cd my-new-project
      git add README.md
      git commit -m "Update README with additional info"
      git push
      git pull
      echo "I'm Member1 and I use Python." >> README.md
   git add README.md
   git commit -m "Member1 update"
   git push
   echo "I'm Member2 and I use Java." >> README.md
   git add README.md
   git commit -m "Member2 update"
    git push
     <<<<<<< HEAD
   I'm Member1 and I use Python.
   =======
   I'm Member2 and I use Java.
   >>>>>>> Member2 update
  I'm Member1 and I use Python.
   I'm Member2 and I use Java.
>   >>>>>> git add README.md
   git commit -m "Resolved merge conflict between Member1 and Member2"
   git push
git checkout -b feature-branch
echo "This project utilizes various technologies." >> README.md
git add README.md
   git commit -m "Add project description in feature branch"
   git push -u origin feature-branch
git checkout master
git merge feature-branch
git commit -m "Merge feature-branch into master"
git push
  
   


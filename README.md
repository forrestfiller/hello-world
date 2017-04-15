# Assembly

### Why? Why not!

### This is the **Built** branch, so you can check your output

1. ``` brew install nasm ```

2. ``` git clone ``` the repo

3. Generate your object file:
 - ``` nasm -f macho64 -o hello_world.o hello_world.asm  ```

( list the contents of your directory to see if you made anything new... )

4. Link the object file:
 - ``` ld hello_world.o -o hello_world  ```

 5. Run your new executable program:
 - ``` ./hello_world  ```

 Your terminal should print the contents. Hooray!

_1. (B) Extract the "challenges.tar.gz" archive._

_O comando utilizado para descompactar o arquivo solicitado foi:_

```sh
tar -vzxf challenges.tar.gz
```

_2. (B) - Change your working directory to the "challenges" directory that was created when you extracted "challenges.tar.gz"._

_O comando utilizado para mudar para o diretório solicitado foi:_

```sh
cd challenges
```

_3. (B) List the contents of the "challenges" directory._

_O comando utilizado para listar o conteúdo do diretório solicitado (considerando que a pessoa já está no diretório correto) foi:_

```sh
ls
```

_4. (B) Create a new directory named "foo"._

_O comando utilizado para criar um novo diretório com o nome solicitado foi:_

```sh
mkdir foo
```

_5. (I) Create a new directory named "foo/bar/1/2/3"._

_O comando utilizado para criar a estrutura de diretórios foi:_

```sh
mkdir -p foo/bar/1/2/3
```

_6. (B) Remove the directory "foo" and all of its contents._

_O comando utilizado para excluir o diretório indicado e seu conteúdo foi:_

```sh
rm -r foo
```

_7. (B) Print the text "Hello World"._

_Para imprimir o texto no terminal, utilizou-se o comando:_

```sh
echo "hello world"
```

_8. (B) Create a file named "hello.txt" that contains the text "Hello World"._

_O comando utilizado para criar o arquivo com o conteúdo dentro foi:_

```sh
echo "Hello World" > hello.txt
```

_9. (B) Create an empty file named "empty.txt"_

_O comando utilizado para criar o arquivo vazio foi:_

```sh
touch empty.txt
```

_10. (B) Remove the file "empty.txt"_

_O comando utilizado para apagar o arquivo vazio foi:_

```sh
rm empty.txt
```

_11. (I) Find a second way to solve challenge 9._

_Outra forma de criar um arquivo vazio é pelo comando:_

```sh
> empty.txt
```

_12. (I) Find a third way to solve challenge 9._

_Mais uma forma de criar um arquivo vazio é pelo comando:_

```sh
truncate -s 0 empty.txt
```

_13. (B) Copy "hello.txt" and name the copy "goodbye.txt"._

_O comando utilizado para copiar um arquivo e renomeá-lo foi:_

```sh
cp hello.txt goodbye.txt
```

14. (B) Rename "goodby.txt" to "hello_copy.txt".

_O comando utilizado para renomear o arquivo foi:_

```sh
mv goodby.txt hello_copy.txt
```

_15. (I) Prove that the contents of "hello.txt" and "hello_copy.txt" are
    identical._
    
_O comando utilizado para exibir o conteúdo dos dois arquivos, mostrando assim que o conteúdo é igual, foi:_

```sh
cat hello.txt hello_copy.txt
```

_16. (B) Concatenate the contents of "hello.txt" and "hello_copy.txt" and store
    the result in a file named "2_hellos.txt"._
    
_O comando utilizado para concatenar o conteúdo dos dois arquivos e colocar em um terceiro criado foi:_

```sh
cat hello.txt hello_copy.txt > 2_hellos.txt
```

_17. (B) Get the full path of your present working directory ("challenges")._

_O comando utilizado para exibir o caminho da pasta atual foi:_

```sh
pwd
```

_18. (B) List the contents of the "challenges" directory (like challenge 3), but
    show the permissions for each filxse._
    
_O comando utilizado para listar o conteúdo do diretório solicitado e mostrar as permissões (considerando que a pessoa já está no diretório correto) foi:_

```sh
ls -l
```

_19. (B) Append some text to the end of "restricted.txt". It's OK to do this in 2 steps._
    
_Para inserir um texto no final do arquivo solicitado, foi necessário usar o comando abaixo juntamente com o sudo para permitir a ação. "-c" é utilizado para indicar ao shell que o próximo argumento é um comando a ser executado._

```sh
sudo sh -c 'echo "Texto de teste" >> restricted.txt'
```

_20. (B) Run the "hello_executable" program._

_Para rodar o programa, utilizou-se o comando abaixo:_

```sh
./hello_executable
```

_21. (B) Run the "challenge_20" program. It's OK to do this in 2 steps._

_Para tornar o arquivo executável e rodá-lo, foi utilizado o comando:_

```sh
chmod +x challenge_20 && ./challenge_20
```

_22. (B) Compile and run "compile_me.c". It's OK to do this in 2 steps._

_Para compilar o programa e rodá-lo, foi utilizado o compilador C padrão junto ao comando para executá-lo:_

```sh
gcc -o compile_me compile_me.c && ./compile_me
```

_23. (A) Run the "redirect" program and collect all of its output in a file named "output.txt"._

_Para rodar o programa indicado, direcionar sua saída para o arquivo "output.txt" e então o abrir, foi utilizado  o comando:_

```sh
./redirect > output.txt && xdg-open output.txt
```

_24. (B) Get the current date and time._

_O comando utilizado para visualizar data e hora atual foi:_

```sh
date
```

_25. (B) Show all of the running processes on your computer._

_O comando utilizado para mostrar os processos em execução (de todos os usuários) foi:_

```sh
ps aux
```

_26. (B) Show the number of processors/cores in your computer._

_O comando utilizado para mostrar o número de processadores/cores foi:_

```sh
nproc
```

_27. (B) Find out what version of the Linux kernel is currently running._

_O comando utilizado para mostrar a versão do kernel do Linux foi:_

```sh
uname -r
```

_28. (B) Find the file in the "bunch_of_files/" directory that contains the string:
    "You found the needle in the haystack!"_
    
_O comando utilizado para encontrar a String indicada, foi:_

```sh
grep -l "You found the needle in the haystack!" *
```






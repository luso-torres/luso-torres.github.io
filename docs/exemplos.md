# Exemplos

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.



## Code Annotation Examples

### Codeblocks

some `code` goes here.

### Plain codeblock

A plain codeblock:

```
Some code here
def myfunction()
// some comment
```

### Code for a specific language

Some more code with the `py` at the start:

``` py
import tensorflow as tf
def whatever()
```

### With a title

``` py title="bubble_sort.py" linenums="1" hl_lines="8 9"
###
# Código criado com intuito de mostrar algumas das funções básicas no mkdocs
# title -> título
# linenums -> mostra as linhas
# hl_lines -> destaca linhas
###
def bubble_sort(items);
    for i in range(len(items)):
        for j in range(len(items)-1-i):
            if items[j] > items[j+1]:
                items[j], items[j+1] = items[j+1], items[j]     
def whatever()
```         
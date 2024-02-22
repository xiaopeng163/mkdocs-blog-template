---
draft: false 
date: 2024-01-31 
categories:
  - word1
comments: true
authors: [xiaopeng163]

---

# Hello world!

Material for MkDocs is a powerful documentation framework on top of MkDocs, a static site generator for project documentation.1 If you're familiar with Python, you can install Material for MkDocs with pip, the Python package manager. If not, we recommend using docker.

<!-- more -->

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```


=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```


!!! note "Ensure pip always runs in a virtual environment"

    If you set the environment variable `PIP_REQUIRE_VIRTUALENV` to
    `true`, `pip` will refuse to install anything outside a virtual
    environment. Forgetting to activate a `venv` can be very annoying
    as it will install all sorts of things outside virtual
    environments over time, possibly leading to further errors. So,
    you may want to add this to your `.bashrc` or `.zshrc` and
    re-start your shell:

    ```
    export PIP_REQUIRE_VIRTUALENV=true
    ```

  [venv]: https://docs.python.org/3/library/venv.html
  [venv-activate]: https://docs.python.org/3/library/venv.html#how-venvs-work


!!! warning "Theme extension prerequisites"

    As the [`custom_dir`][custom_dir] setting is used for the theme extension
    process, Material for MkDocs needs to be installed via `pip` and referenced
    with the [`name`][name] setting in `mkdocs.yml`. It will not work when
    cloning from `git`.

???+ note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.
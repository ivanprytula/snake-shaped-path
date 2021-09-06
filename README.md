# snake-shaped-path
Mastering Python

## Use flake8
```shell
flake8 <file_name.py>
```

## Use black
```shell
# 
black <file_name.py> --check

# -S, --skip-string-normalization: Don't normalize string quotes or prefixes.
black <file_name.py> -S

#  --diff Don't write the files back, just output a
#                                  diff for each file on stdout.
# --color / --no-color            Show colored diff. Only applies when
#                                  `--diff` is given.
black --diff --color main.py
# Format all files in dir
black .
```

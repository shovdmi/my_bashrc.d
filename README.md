add to the end of your ~/.bashrc

```
current_script_path=$(dirname "${BASH_SOURCE[0]}")
source $current_script_path/my_bashrc.d/my_bashrc.source
```

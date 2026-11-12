# DirTree

Finds the directory tree of the current working directory or a user-specified directory. The directory structure can be printed to the terminal and saved to a text file.

## Usage Instructions

### 1. Install the tool

```bash
pip install git+https://github.com/jcapecci09/DirTree.git
```


### 2. Verify Installation
```bash 
dirtree --help
```

3. Run tool
```bash 
dirtree
```

4. Use command flags
```bash
dirtree -i src -o dir2.txt --print
```

## Commands flags

| Flag | Long Option | Description | Default |
|---|---|---|---|
| `-i` | `--input` | Directory path to inspect | Current working directory |
| `-o` | `--output` | Output text file name/path | `dir.txt` |
| `-d` | `--depth` | Maximum directory depth to inspect | `2` |
| N/A | `--print` | Print directory structure to terminal | `False` |
| N/A | `--show_hidden` | Include hidden files and directories | `False` |
| `-h` | `--help` | Display help information | N/A |

## Example output
```text
📁 DirTree/
    📄 README.md
    📄 pyproject.toml
    📁 src/
        📁 dirtree/
            📁 test/
            📄 cli.py
```

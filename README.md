# Typescript project initializer

My shell script to create an empty project starting from the template in `https://github.com/paolodenti/ts-template`.

## How to use it

```bash
./create-ts <destination folder> <project name> [https git remote repo [git main branch]]
```

### Examples

#### create local project

```bash
./create-ts ~/new_folder myproject
```

#### create project with git remote

```bash
./create-ts ~/new_folder myproject git@github.com:paolodenti/newproject.git master
```

## Dependencies

The following excutables must be in path to run `create-ts`.

* `npm`
* `git`
* `jq`

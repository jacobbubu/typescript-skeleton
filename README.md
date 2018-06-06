# typescript-skeleton
> Create a full-featured Typescript project as quickly as possible

## Usage

```
git clone https://github.com/jacobbubu/typescript-skeleton quick-ts
```

then create a alias in your shell `.rc`, for example: `.bashrc`.

```
alias newts='function _newts(){newDir=`{path/to}/quick-ts/newts $@ | tail -1`;cd $newDir;tree ./ -L 1};_newts'
```

Please pay attention to replace the path inside curly brackets.

```
source ~/.bashrc
newts your_ts_project_name
```

## What's inside?

This skeleton includes:
* jest as test harness
* lint  at git commit
* commitizen, conventional-changelog
* travis and coverall

## License
 MIT

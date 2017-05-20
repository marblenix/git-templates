# INTRODUCTION

These are my git templates. You can use them as well. You're going to need Ctags.

On mac:

```
brew install ctags
```

Elsewhere:

http://ctags.sourceforge.net/

# INSTALLATION

Begin by cloning this repository:

```
git clone https://github.com/marblenix/git-templates.git ~/.gittemplates
```

Then configure git to use these templates:

```
git config --global init.templateDir ~/.gittemplates
```

If you already have a few git repositories downloaded you can install my git
hooks into your local repository by changing directories to your repository and
running:

```
git init
```

If you want to overwrite existing git hooks into your existing repository you
must rename or remove the git hooks in the .git/hooks directory.

# CTAGS

If you use vim this will automatically work with vim's builtin Ctags support.
Change directory to your repository and open vim and type `:tag <word>` and vim
should open the file and bring you to the line with the definition of that word.

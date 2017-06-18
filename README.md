git-dad: enjoy your typos
=======

`git-dad` allows you to recover when you've accidentally mistyped `git add`,
and instead typed `git dad`.  Normally, Git will tell you that you've made
a mistake:

```
% git dad foo.c
git: 'dad' is not a git command. See 'git --help'.
```

But with `git-dad`, your file will still be added to the index.  Though not
without a bit of punishment for your typo:

```
% git dad foo.c
What do you call corn that joins the army? Kernel.
% git status --short
A foo.c
```

That's right, you get a dad joke!

All you have to do is put `git-dad` in your path to enjoy the puns:

```
% git dad bar.c
Why do bears have hairy coats? Fur protection.
```

Brilliant!


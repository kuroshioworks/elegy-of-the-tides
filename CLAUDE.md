# Notes for Claude

## Commit author / コミットの作者

Never put a personal email address (such as a Gmail address) in commits to this
public repository. Before committing, set the author for this repository to the
GitHub noreply address:

```
git config user.name "Kuroshio Works"
git config user.email "295988111+kuroshioworks@users.noreply.github.com"
```

Check with `git config user.email` before every commit. The GitHub account blocks
pushes whose latest commit exposes a private email, so a commit with a personal
address will be rejected on push.

このリポジトリは公開されているため、コミットに個人のメールアドレス（Gmail など）を
使わないでください。コミットの前に、上記の noreply アドレスを設定してください。

## Copyright / 著作権

All rights reserved (see LICENSE). Every page's footer carries the copyright and
the no-reprint / no-AI-training notice; add the same footer to any new page.
新しいページを追加するときも、既存ページと同じ著作権表示のフッターを付けてください。

```
git config --global alias.acp "!f() { git add -A && git commit -m \"$@\" && git push; }; f"
```

usage
git acp "commit text here"

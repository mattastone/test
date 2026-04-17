write a joke.  
append it to the file called JOKES.md

```bash
git config user.email "164589+mattastone@users.noreply.github.com"
git config user.name "Joker"
git add JOKES.md
git diff --cached --quiet || git commit -m "Joke Store session $(date +%Y-%m-%d)"
git push origin HEAD:main
```
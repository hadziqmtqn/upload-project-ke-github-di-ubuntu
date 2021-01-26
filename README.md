# Upload Project ke Github di Terminal Ubuntu
## Buat repository baru
## Login ke github lewat terminal ubuntu
dan arahkan tepat didalam folder project. contoh : verval@ID:~project/man2banyumas_ppdb$
```bash
git config --global user.name "UsernameAnda"
```
```bash
git config --global user.email IsiDenganEmailAnda@gmail.com
```
## Proses upload
```bash
git add .
```
```bash
git commit -m "first commit"
```
```bash
git branch -M main
```
```bash
git remote add origin https://github.com/hadziqmtqn/nama-project.git
```
```bash
git push -u origin main
```

Sumber :
https://www.niagahoster.co.id/blog/git-tutorial-dasar/
https://www.geeksforgeeks.org/how-to-install-configure-and-use-git-on-ubuntu/

```bash
📁project-root/
|--🗃️assets
| |--📷images
|    |--content1.png
| |--✨style
|    |--index.css
|--about.html
|--index.html
```

## tutorial gitbash:

1. untuk membuat folder repo

```bash
   git init
```

2. configurasi

   ```bash
   git config --global user.name "[username anda]"
   ```

   ```bash
   git config --global user.email "[email anda]"
   ```

3. cek status branch

```bash
  git status
```

4. jika masih master ubah menjadi main

```bash
   git branch -m main
```

5. masukkan perubahan kedalam staging

```bash
   git add .
```

6. remote ke repo anda

```bash
   git remote add origin [url-repo]
```

7. tambahkan keterangan pada perubahaan

```bash
   git commit -m "[keterangan]"
```

8. kirim ke repo

```bash
  git push -u origin main
```

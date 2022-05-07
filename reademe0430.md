## 本日心得   
有一點忘記初衷, 確實有一些人無程式背景, 且沒有老師, 完全靠自己去學習。   
在安逸的環境待久了, 都忘記那位當初只是想要而做的自己   
把樂趣放在錯誤的地方了   

```
# 更改完檔案輝先放在工作區

# 把檔案add 後, 才會進入 staged 區域   
git add a.txt

# 下一步 commit 後, 才會進入 repo 區域
git commit -m "message"

# ----上面都是git 操作 ----

# 最後一步 push 上傳到 server 端   
git push 


```

![](https://i.imgur.com/iYbhwu4.png)

| window | 說明 |
| -----|------|
| touch | 新建檔案 |
| mkdir | 建立資料夾 |
| copy | 複製 |
| move | 移動 |
| del | 刪除檔案 remove |
| cls | 清除 |


```bash=
# 檢視分支
git branch

# 新增分支
git branch {branch-name}

# 切換分支
git switch {branch-name}
git checkout {branch-name}

# 合併分支
# 先切換到 main
git switch main
# 再合併進來
git merge seconds

# 刪除本地分支
git branch -d {branch-name}

#github
git remote add origin http:
git branch -M main
git push -u origin main

git branch -M second
git push -u origin second
```

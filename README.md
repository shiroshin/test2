# TEST2
## git push
git remote add origin [url]  
git commit -u  
git push -u origin master

## fatal : remote origin already exists
### fatal: remote origin already exists が出た場合
既にoriginが追加されている  
git config --listを実行する  
remote.origin.url=[url]  
remote.origin.fetch=  
があることを確認できる
### 対処法
 git remtoe rm origin を実行する<br>

 configのremote.originが消えていることを確認してから<br>
 もう一度git remote add origin を実行する

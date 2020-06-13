#### 1、查看状态

```javascript
git status
```

#### 2、提交到暂存区

```javascript
git add 文件名.后缀
```

#### 3、把暂存区文件提交到分支

```
git commit -m '文件信息'
```

首次提交需要配置

```javascript
 git config --global user.email "you@example.com" 
 git config --global user.name "Your Name"  
```

#### 4、回滚

```
git reset  版本号
```

#### 5、回到回滚前状态

```
git reflog    
349c139 (HEAD -> master) HEAD@{0}: reset: moving to 349c139488e0
250634e HEAD@{1}: commit: 增加一个回滚
git reset  版本号（250634e） 
```

#### 6、强制回滚

```
git reset  版本号（250634e） --hard
```

#### 7、获取公钥和私钥

```
ssh-keygen -t rsa -C "you@example.com" 
```

#### 8、当前文件夹代码与远程库进行关联

```
git remote add origin git@github.com:oscar776/study.git(远程库地址)
```

#### 9、把本地所有代码推送到仓库

```
git push -u origin master 
```


#### 10、创建分支
```
git branch dev(分支名)
git checkout dev   --切换分支
```
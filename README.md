# Git - The Simple Guide

Vào link này nhé:
https://yugiking0.github.io/huongdan-github/index.vi.html

Các câu lệnh:

1. Tạo nhánh trên máy và chuyển qua:

```
   git checkout -b develop

   git checkout develop
   git checkout debug
```

2. Thêm các file thay đổi cần Update

```
   git add \*
```

3. Mô tả các thay đổi:

```
   git commit -m "Ghi chú Commit cho nhánh Develop"
   git commit -m "Ghi chú Commit cho nhánh Debug"

```

4. Đẩy lên nhánh

```
git push origin master

git push origin debug


git push origin develop
```

5. Xóa các nhánh

```
git branch -d develop

```

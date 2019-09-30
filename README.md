

### Repository 동기화
```
cd C:\PatternRecognition 
git clone https://github.com/unizard/quiz.git
git status
```

### Master branch로 코드 Commit
```
git add 20190924_Quiz.py
git commit -m "Quiz1"
git push
git add 20190930_Quiz_solution.py
git commit -m "Quiz2"
git push
```

### Sub-Branch 생성
```
git branch solution
git checkout solution
```

### 코드 생성 및 수정
```
// 20190924_Quiz_solution.py 만들고 수정
```

### Sub-branch로 코드 commit
```
git add .
git status
git commit -m "Quiz1-solution"
git push origin solution
```

### Sub-branch 코드 master 에 통합하기
```
git checkout master
git merge solution
git push
```

### Branch 삭제
```
git branch –d solution
git push origin --delete solution
```

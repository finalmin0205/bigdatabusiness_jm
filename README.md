# 📖자기주도 학습 

###  1.READEME에서 테이블 만들어보기
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |****


### 2.GIT 6가지 설정
#### 2-1. 사용자 이름 설정
git cofnig --global user.name jm choi

#### 2-2. 전자메일 설정
git config --global user.email finalmin0205@naver.com

#### 2-3. 자동 줄바꿈 설정
git config --global core.autocrlf ture

#### 2-4. 안전 줄바꿈 설정
git config --global core.safecrlf false

#### 2-5. 기본 편집기 설정
git config --global core.editor 'code --wait'

#### 2-6. 기본 브랜치이름 설정
git config --global init.defaultBranch main


### 3. 깃 저장소 basic설정
#### 3-1. 저장소 생성
git init basic

#### 3-2. 폴더이동
cd basic

### 커밋
echo aaa > hello.txt (hello.txt파일에 aaa를 저장함)
cat hello.txt (hello.txt에 있는 문자를 출력)
git add hello.txt (깃 저장소 스테이징 영역에 저장)
git commit -m A (깃 저장소에 저장)


![image](https://github.com/finalmin0205/bigdatabusiness_jm/assets/144201052/970e1d15-17c3-4f38-8175-e17eee3de57c)

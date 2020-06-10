# ls

## ls 명령어
list 의 약어로 현재 디렉토리에 존재하는 파일들의 목록을 출력한다.

## ls 명령옵션 
l : 각 파일 들의 생성일자, 수정일자, 권한 등 세부정보들을 표시한다.
a : 숨긴 파일을 포함한 모든파일들을 보여준다.

## ls 사용법
ls [-옵션] 
ex) ls -al, ls -l



# rm 

## rm 명령어
remove의 약어로 지정한 파일들을 삭제한다.

## rm 명령어의 옵션
r : 디렉토리도 삭제한다.
f : 질문없이 강제로 삭제한다.

## rm 사용법
rm [-옵션]
ex) rm -r, rm -rf



# cd

## cd 명령어
change directory의 약어로 현재사용자의 디렉토리 위치를 변경한다.

## cd 사용법
cd {절대경로 or 상대경로}

### 절대경로란?
root부터 시작하는 경로
ex) /home, /home/사용자폴더

### 상대경로란?
현재위치를 기준으로 나타내는 경로
ex) 현재위치가 사용자 폴더이다(pwd = /home/사용자폴더)
cd .. -> /home
cd ../.. -> /
cd download -> /home/사용자폴더/download
cd . -> /home/사용자폴더

ex2) pwd는 /usr
cd .. -> /
cd ../home -> /home
cd ../home/사용자폴더/download -> /home/사용자폴더/download

#### /와 /root의 차이
/는 system root 폴더로 최상위 폴더가 된다.
/root 최상위 루트폴더 안에 있는 그냥 이름이 루트인 폴더로 이 루트폴더는 부트로더에 의해 root폴더로 사용되고 , 부팅완료가 된 후에 /root에 위치한다.

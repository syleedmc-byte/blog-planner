# 블로그 월간 플래너

동그라미를 끌어다 놓으며 월간 블로그 플랜을 짜는 페이지예요. 주소는 아래 형태가 돼요.

`https://<깃허브 아이디>.github.io/<저장소 이름>/`

## 처음 한 번만

1. github.com에서 새 저장소를 만들어요. 이름 예: `blog-planner`
2. 이 폴더에서 아래를 실행해요.

```bash
git init
git add .
git commit -m "블로그 월간 플래너"
git branch -M main
git remote add origin https://github.com/<깃허브 아이디>/blog-planner.git
git push -u origin main
```

3. 저장소의 Settings > Pages에서 Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 두고 Save를 눌러요.
4. 1~2분 뒤 위 주소로 열려요.

## 일정 바꾸기

1. 페이지에서 동그라미를 옮기고 고쳐요. 옮긴 내용은 내 브라우저에 임시 저장돼요.
2. 아래쪽 "저장 파일 받기"를 눌러 `months.json`을 받아요.
3. 받은 파일로 이 저장소의 `data/months.json`을 덮어쓰고 `git add`, `commit`, `push`를 해요.
4. 1~2분 뒤 모두에게 같은 일정이 보여요.

파일을 올리기 전까지는 내 브라우저에서만 바뀌어 보여요. "내 변경 지우기"를 누르면 저장소의 일정으로 돌아가요.

## 알아둘 점

- 저장소가 공개면 주소를 아는 누구나 이 페이지를 볼 수 있어요. 이 데이터에는 인터뷰 대상자 이름을 넣지 않았어요.
- 비공개 저장소로 Pages를 쓰려면 유료 플랜이 필요해요.

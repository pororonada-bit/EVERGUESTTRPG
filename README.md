# EVER QUEST TRPG prototype

## GitHub Pages 배포
1. 저장소에서 **Add file → Upload files**를 누릅니다.
2. `index.html`과 `README.md`를 업로드하고 **Commit changes**를 누릅니다.
3. **Settings → Pages**로 이동합니다.
4. **Deploy from a branch**를 선택하고 Branch `main`, Folder `/(root)`를 지정한 뒤 Save를 누릅니다.
5. 잠시 기다린 뒤 Pages 화면에 표시되는 사이트 주소를 엽니다.

## 현재 포함된 기능
- 8개 직업 캐릭터 시트 및 HP 조정
- 1d6 / 2d6 / 3d6 / 1d20 굴림
- 기본 판정 버튼, 채팅 로그
- 장면 이름, 배경 이미지 업로드, 드래그 가능한 토큰
- 브라우저 localStorage 저장

## 중요
현재는 프런트엔드 시제품이며, 채팅/캐릭터/맵은 같은 브라우저에만 저장됩니다. 여러 사람이 서로 다른 기기에서 실시간으로 플레이하려면 Supabase 데이터베이스, Realtime, Storage 및 접근 정책을 추가로 연결해야 합니다. 노트의 판정 규칙 일부는 사진에서 판독 가능한 범위로 임시 구현했으므로 실제 플레이 전에 수치와 예외 규칙을 검증해야 합니다.

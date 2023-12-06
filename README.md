# UnrealProject-2022_9-12

2022-09 ~ 2022-12 동안 진행한 프로젝트 입니다.

맵
-------------
- 맵의 경우 사막, 바다, 설원, 숲등의 지형을 언리얼의 랜드스케이프 기능을 이용하여 구현해 보았습니다.  
- 각 지형 마다의 특색있는 bgm을 따로 설정해 주었습니다.

***
![img1 daumcdn](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/21347148-4936-469e-a8c0-f2873ddcacb3)
![img1 daumcdn](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/7d1f7613-aa00-42d3-8188-aed368da1065)


   
![img1 daumcdn](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/32cfab05-5993-4cab-a2cb-3db3cef27c80)
![img1 daumcdn](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/bfdf1148-d830-406b-bc09-8b605ef68266)
![img1 daumcdn](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/c8e62508-19ba-4907-9882-b3a7c60acd67)
![img1 daumcdn](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/f5aa8f53-f476-4ddc-bd2d-c90524c3bc15)
***
   
   
   
      
캐릭터   
-------------
- 캐릭터의 경우 아래와 같이 원거리/근거리 캐릭터를 선택할 수 있도록 하였습니다.

<img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/bb544765-1d21-440c-a7df-adf91dc6a3a3" width="50%" height="50%"></img>

- 몬스터와 일부 npc들을 blender와 무료 텍스쳐를 통해 제작해 보았습니다.
- 이동, 공격 모션 또한 뼈대를 구축하여 제작해 보았습니다.

   <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/1024c0b6-9ffb-41a7-9b07-18db08709f78" width="50%" height="50%"></img>
***



기능
-------------   
- 기본적인 멀티 플레이
  - 데디케이티드 서버를 이용한 멀티플레이 기능 구현
  - 플레이어 목록/ 채팅을 위한 id 부여   
  
   <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/c137dc66-acb5-43fe-9c6e-da7cee1b4f10" width="50%" height="50%"></img>

***   
- 맵 시스템 (미니맵/전체맵)
  - 9구역으로 구분하여, 지형/배경음악등을 조절
     
  <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/5e24ebcc-9440-4f98-a35c-6ab0bcc35d22" width="50%" height="50%"></img>
  ![image](https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/57872dc8-2934-464d-957a-4b3508e9a5f9)

***   
- 몬스터 관련 시스템(공격, 드랍, 데미지, 리스폰)
  - 구역별 난이도에 따라 몬스터 배치 (총 7종)
  - 이동 반경 내 랜덤 이동 ai 장착
  - 데미지, 드랍 아이템 등, dataTable을 이용하여 관리
      
  <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/aeb87b3f-571c-46bd-a7e3-626dc83be09f" width="50%" height="50%"></img>
  
  
***  
- 캐릭터 관련 시스템 (사망, 공격력, 방어력, 레벨업 등)
  - 하단의 경험치 상태바, 좌측 상단의 캐릭터 정보ui
      
<img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/dc67ae30-4087-4625-8333-d3d2fbf8dc71" width="50%" height="50%"></img>
   
***  
- 인벤토리 시스템
  - 드래그 & 드롭을 통한 인벤토리 배치 기능
  - 아이템 id에 따른 인벤토리 관리 기능
  - 더블클릭을 이용한 아이템 사용 기능
 
     
  <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/2db31b29-e10d-4bbe-8b81-5bd5e250c98e" width="30%" height="30%"></img>

***   
- 장비창 시스템
  -  장착한 장비에 대한 캐릭터 상태 연동 (방어력, 공격력)
  -  더블클릭을 통한 장착/해제
     
  <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/9814f218-8654-4cfc-a62e-c9fab60d30dd" width="30%" height="30%"></img>

***   
- 강화 시스템
  - 강화석을 이용한 아이템 강화방식
  - 추가 확률을 위한 기능 추가
  - 성공/실패/유지 등의 상황 연출
     
<img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/5070ea7c-c6c7-4ced-8295-4a2dfdbc37ee" width="45%" height="45%"></img>
<img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/53bee570-3ca5-4a23-bef0-046368cee243" width="40%" height="40%"></img>



***   
- 아이템 구매(상점), 아이템 사용 시스템
  - 플레이어의 인벤토리와 연동
  - 구매/판매 등의 기능 구현
     
  <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/1e48673b-aedf-4e27-a039-dbb7f7db7f83" width="50%" height="50%"></img>

***   
- 채팅 시스템
  - 플레이어 id를 통한 식별
     
  <img src="https://github.com/jhyun-lee/UnrealProject-2022_9-12/assets/100923108/f333691b-e1c8-43d2-a8c7-24a6ff625af4" width="50%" height="50%"></img>



그 외 시스템  
- 단축키 시스템
- npc 랜덤 이동 시스템
- 환경설정 시스템

자세한 내용은 아래에서 확인 가능합니다. 
Blog : https://ljhyunstory.tistory.com/251
YouTube : https://www.youtube.com/watch?v=JC8OpP2VZQo

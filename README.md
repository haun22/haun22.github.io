# 게임명: What?! [디자이너: 김정우]
## 목차
### 1. [컨셉](#컨셉)
### 2. [관련 이미지와 동영상](#관련이미지와-동영상)
### 3. [대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#컨셉과-대표이미지-기반-작품묘사)
### 4. [what의 구성 요소](#구성요소)
### 5. [게임 시스템 디자인](#게임-시스템-디자인)
### 6. [요구사항](#요구사항)
### 7. [프로토타입 개발 요구사항 (6주개발)](#프로토타입-개발-요구사항-(6주개발))



# 컨셉

### 메인컨셉 : 어려움
 유저가 게임을 플레이하면서 다양한 어려움에 직면하고 해결하가야할것이다 . 
 <hr>

### 서브 컨셉 1 : 간단함 
 어려운게 굳이 복잡할 필요는 없다고 생각합니다. 그래픽과 이동을 간단하면서 어려움을 추구하여 피로감을 덜 쌓게 하고 싶다.
 <hr>
 
### 서브 컨셉 2 : 다양함 
난이도를 조절함에 있어 다양한 방해요소는 필수적이라고 생각함. 애너미라든지 오브젝트 요소를 추가하여 다양한.어려움을 느낄수 있게 하고싶게 할것.
<hr>

### 서브 컨셉 3 : 시간 
올라가는 시간을 타이머로 재어 경쟁요소를 추가할 것. 어려운것을 남들보다 더한 속도로 쟁취했을때 성취감을 느낄 수 있게 만들고 싶게 만들것
<hr>

### 서브 컨셉 4 : 사운드 
 bgm을 경쾌하고 유쾌한 bgm을 추가하여 어려운 난이도여도 불쾌함을 없애고 좀더 재밌게 즐기게 하게할것, 단 어둡고 몽환적인 음악도 추구할 수 있음 .
 <hr>
 
### 서브 컨셉 5 : 조작감 
난이도를 조절함에 있어서 조작감의 불편함과 깨끗함의 정도는 차이가 없어야 한다고 생각합니다. 조작감 같은것은 편하게 만들고 싶습니다




# [관련이미지와 동영상]
## 이미지 
![image](https://user-images.githubusercontent.com/101154001/195365871-fcbdd7a9-d4e7-4c1a-b635-c6678e629b8d.png)

## 동영상 
[![video label](https://user-images.githubusercontent.com/101154001/196812527-eaebf9cb-0190-4527-a827-ebdac283bfd9.jpg)](https://www.youtube.com/watch?v=ZNB80iDaEAQ&t=198s)




# [대표 이미지]

![image](https://user-images.githubusercontent.com/101154001/196812873-cf7671b4-6d87-401e-9b58-c927a5a0565c.jpg)

# [컨셉과 대표이미지 기반 작품묘사]
### 대표이미지 기반 
 

플레이어: 플레이어 캐릭터을 가지며, 직접 유저가 플레이할 수 있는 오브젝트

타이머: 현재 플레이어가 스테이지에서 진행중인 시간을 나타내는 오브젝트

옵스타클: 플레이어가 닿으면 죽음이라는 변수를 줄 수있는 정지된 오브젝트

애너미: 플레이어가 닿으면 죽음이라는 변수를 줄 수 있는 움직이는 오브젝트

<hr>





# 구성요소

## [<게임제목> 구성 요소]
What?!
What?! : 이게 왜? 라는 말이 나올정도로 어려운 게임을 만들고 싶어서 what?! 이라는 제목으로 구성요소를 정함.



# 1. 메커니즘
## [도전 과제] 

1. 스테이지 어딘가에 있는 클리어 오브젝트에 도착함으로써 스테이지를 클리어.
2. 스테이지 타이머로 랭킹 측정.

## [재미 요소] 

1.어려운 난이도로 인한 도전욕구.

2.몽환적인 분위기와 사운드로 인한 편안함, 혹은 역동적이고 활발한 사운드에 비한 어두운 분위기

2.다양한 장애물과 애너미를 추구.

2.간단한 조작으로 간단함을 추구.


# 2. 이야기


## [만들게 된 배경]

디 엔드 이즈나이라는 게임과 점프킹이라는 게임을 예전에 해보았던 기억이 났는데 간단한 조작법이지만 그로 인한 난이도는 결코 간단하지
않다는것이 매력적으로 다가와서 이런 게임을 나도 만들면 어떨까? 생각이 들어서 만들게 되었습니다.
## [카메라 관점]

2d뷰를 사용하고 2d 스탑뷰로 인해 멀미증세 완화




# 3. 미적요소
## [디자인] 
![image](https://user-images.githubusercontent.com/101154001/196813806-e7c3c5c3-edaf-4550-bd82-84914bf75775.jpg)


## [컬러] 
![image](https://user-images.githubusercontent.com/101154001/196813626-3601400a-295a-4d71-9a8e-6b1264d7b286.jpg)


## [음향]  
몽환적인 느낌과는 다르게 역설적으로 신나는 음악을 채용할까 생각중이지만
몽환적인 느낌의 음악도 괜찮을거 같아 고민중임.

# 4. 기술
## [플레이어]  
키보드 방향키 → ←를 사용하고 점프키 space키를 사용함.

# 게임 시스템 디자인

## 1.게임오브젝트 분해 
  
  | 연번 | 오브젝트 이름 | 오브젝트 이미지 |
  |:---:|:---:|:---:|
  |1|player|![image](https://user-images.githubusercontent.com/101154001/196831116-28c464a9-4b86-4fc2-91cb-82bc7856c10d.png)|
  |2|timer|![image](https://user-images.githubusercontent.com/101154001/196831215-69bfea7c-e02d-4ca4-b57a-b62a6fca8f82.png)|
  |3|enemy|![image](https://user-images.githubusercontent.com/101154001/196831264-187e07bd-98d3-45a3-9bc5-6650375471f2.png)|
  |4|obstacle|![image](https://user-images.githubusercontent.com/101154001/196831359-f661aecd-7740-4010-966c-ed8cb4a0c2a6.png)|





## 2.파라미터 (속성) 

### 1.player

|속성|영문명칭|설명|
|:---:|:---:|:---:|
|스피드|Speed|플레이어블캐릭터의 속도|
|점프|jump|플레이어블캐릭터의 점프력|
|상태|playerST|플레이어블 캐릭터의 행동 상황|

### 2.obstacle

|속성|영문명칭|설명|
|:---:|:---:|:---:|
|스피드|obspeed|장애물의 속도|
|상황|obst|장애물의 상황|

### 3.enemy

|속성|영문명칭|설명|
|:---:|:---:|:---:|
|스피드|espeed|애너미 캐릭터의 속도|
|점프력|jump|애너미 캐릭터의 점프력|

## 3.행동 뽑아보기

### 1.player 

|행동|영문명칭|설명|
|:---:|:---:|:---:|
|정지상태|stop|아무 행동도 하지 않는다.|
|점프|jump|플레이어가 점프키를 입력받아 점프를 함|
|오른쪽으로 이동|right|플레이어가 오른쪽키를 입력받아 이동함|
|왼쪽으로 이동|left|플레이어가 왼쪽키를 입력받아 이동함|
|죽음|death|플레이어가 장애물과 애너미에게 죽어 있는 정지한다.|

### 2.enemy

|행동|영문명칭|설명|
|:---:|:---:|:---:|
|정지|stop|애너미가 정지해 있다.|
|이동|move|애너미가 움직이고 있다.|


## 3. 상태 뽑아보기

### 1.player

|속성|영문명칭|설명|
 |:---:|:---:|:---:|
|정지 상태|stop|키를 입력받지 않고 있어 정지해 있는 상태|
|점프|jump|플레이어가 점프키(space)키를 입력받아 점프를 하고 있는 상태|
|오른쪽으로 이동|right|플레이어가 오른쪽(키보드→)키를 입력받아 오른쪽을 이동하는 상태|
|왼쪽으로 이동|left|플레이어가 왼쪽(키보드←)키를 입력받아 왼쪽으로 향해 이동하는 상태|
|죽음|death|플레이어가 장애물과 애너미에게 피격받아 죽어있는 정지상태|

### 2.enemy
|속성|영문명칭|설명|
|:---:|:---:|:---:|
|피격|punch|애너미가 플레이어와 피격판정이 나고 있는 상태|
|이동|move|애너미가 정해진 알고리즘에 따라 움직이고 있는 상태|

### 3.obstacle

|속성|영문명칭|설명|
|:---:|:---:|:---:|
|피격|punch|장애물이 플레이어와 피격판정이 나고 있는 상태|
|이동|move|장애물이 정해진 알고리즘에 따라 움직이고 있는 상태|


## 4.플레이어 캐릭터 속성(파라미터)

|속성|영문명칭|설명|
|:---:|:---:|:---:|
|위치|location|플레이어가 현재 있는 위치|
|상태|stat|플레이어가 키를 입력받아 행동하는 상태|
|죽음|dead|플레이어가 지정되지 않은 (enemy,obstacle) 오브젝트에 피격당해 죽어있는 정지상태|

## 4.게임의 규칙

플레이어는 지정된 좌측 위치에서부터 시작해 목표 오브젝트에 도달하는것이 목표.

플레이어는 목표 오브젝트에 도달하기 위해서 방해 오브젝트(enemy,obstacle)에게 피격받지 않고 가야함.

플레이어가 목표 오브젝트에 도달시 다음 스테이지 및 이번 스테이지 반복 가능.

지정된 스테이지별로 캐릭터의 방해 오브젝트의 종류는 다르다.


## 5.게임에 사용할 공식 

플레이어 사망:(player object가 enemy,obstacle)오브젝트와 부딪힌 상태)

플레이어 이동:(play object가 지정된 키를 입력 받아 움직임)

스테이지 클리어(player object가 목표에 도달함)























# 요구사항

## 시작화면
화면위에는 what?!이라고 적혀있는 텍스트가 있다.

what?!이라는 텍스트 아래에 화면 중앙에 game play, potion,credit,end 버튼이 세로로 정렬되어 있다.

gameplay 버튼은 게임을 스테이지별로 진행 할수있는 게임화면이다.

스테이지는 클리어한 다음 스테이지부터 플레이가능하다.

option은 설정 화면으로 이동하며 설정화면에는 사운드를 조절할수 있다.

credit화면은 제작자를 메시지로 띄워준다.

end버튼은 게임을 종료함.

## 게임화면
게임 좌측 상단 플레이어가 얼마나 죽었는지 표시되며 우측 상단엔 진행시간이 표시된다.

플레이어는 좌측부터 우측에 있는 목표 오브젝트까지 이동한다.

스테이지는 존재하며 한 스테이지를 클리어시 다음 스테이지를 갈것인지 리트라이를 할것인지 버튼이 next,retry 두 버튼이 존재한다.

조작은 키보드 화살표, 좌우는 이동, space키는 점프이다.

게임오버의 조건은 플레이어가 장애물에 걸리거나 애너미에 닿았을시 즉시 종료된다.

게임클리어의 조건은 플레이어가 지정된 위치에 도달하거나 지정된 오브젝트를 먹었을시 종료된다.

게임 종료 시 종료 팝업이 뜬다. 종료팝업에는 retry버튼 메인화면 버튼이 존재한다.

타이머의 경우에는 진행시간및 스테이지를 깬시간이 존재한다.

스테이지를 깼을경우 게임 메뉴 버튼or스테이지 종료시 최단 시간을 표기한다.




# 프로토타입 개발  (6주개발)

## 1주차 캐릭터 이동구현

캐릭터 이동에 필요한 player script 

캐릭터 점프에 필요한 player script

캐릭터 구현에 필요한 이미지,asset 

## 2주차 게임 화면 디자인
게임 메인화면에 들어갈 메뉴 텍스트,what?!문구 디자인 

디자인한 화면 버튼스크립트 제작

## 3주차 게임 진행에 필요한 스테이지 맵 디자인 
스테이지 맵 디자인 및 ui 제작

## 4주차 스테이지 맵에 들어갈 애너미 장애물 오브젝트 디자인및 스크립트

맵에 들어갈 애너미,장애물 오브젝트및 스크립트 생성




## 5주차 스테이지 버튼, 리트라이 버튼 타이머 버튼 제작

스테이지 메뉴,리트라이 버튼 제작.

## 6주차 캐릭터와 오브젝트 상호작용

캐릭터와 애너미,장애물 오브젝트에 상호작용

게임 시작화면,스테이지화면,메뉴화면 상호작용 

# 프로토타입 개발 요구 사항(6주개발)

## 1주차 캐릭터 이동구현

~캐릭터 이동에 필요한 player script (100)~

~캐릭터 점프에 필요한 player script (100)~

~캐릭터 구현에 필요한 이미지,asset (100)~

## 2주차 게임 화면 디자인
~게임 메인화면에 들어갈 메뉴 텍스트,what?!문구 디자인 (80%인 이유 : 디자인 배경 이미지 다시 추가예정 구색만 입혀놈)~

~디자인한 화면 버튼스크립트 제작, 크레딧,옵션 화면 신 구현 (33%)~

## 3주차 게임 화면 디자인 및구현
~스테이지의 지형,ui 구현 (맵 지형 디자인 요소) (50: 맵의 디자인 ui구현은 해놓았으나 바닥 그라운드를 제외한 점프 그라운드 스크립트가 오류로 작동을 안함 고쳐야함)~

~애너미의 위치, 장애물의 위치 지정및 구현. (50% 스크립트 미비로 인해 장애물의 위치지정및 애너미의 위치는 구현하였으나 충돌로 인한 활동 미구현 )~

~스테이지 클리어에 필요한 목표 지점, 아이템 구현 (50% 이유: 목표 지점및 아이템 구현은 끝내놓았지만 지형및 애너미의 충돌 미구현으로 실행 불가 )~

## 4주차 구현


게임 그라운드 리지드 바디 콜라이더 수정하기 (0)

장애물 추가구성해보기 (0)

애너미, 클리어 오브젝트 구현(0)

그라운드 맵 추가구현 (0)

플레이어 에셋 수정후 스크립트 수정(0)


현재  펄볼 에셋 오류로 인해 모든 유니티 기능정지로 인하여

저번주에 짜논것들을 스크립트와 에셋까지는 복구시켜놓았음.

## 5주차 구현

## 6주차 구현 
















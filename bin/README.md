# 관통프로젝트: 
### 프로젝트이름 : EnjoyTripSpring
### 제출일: 2023.11.03일

### 참여 페어
- 지인성(조장), 양유경

### 처리된 요구사항 목록
  
|난이도|구현기능|세부|작성여부(O/X)|
|:---:|---|---|:---:|
|기본|메인페이지||X|
|기본|회원관리|회원정보 등록|O|
|기본|회원관리|회원정보 수정|O|
|기본|회원관리|회원정보 삭제|O|
|기본|회원관리|회원정보 검색|O|
|기본|로그인/로그아웃||O|
|기본|관광지 정보 관리|전체검색|O|
|기본|관광지 정보 관리|상세 조회|O|
|기본|관광지 정보 관리|지역별 조회|O|
|기본|관광지 정보 관리|관광지 종류별 조회|O|
|추가|나만의 여행 계획 관리||X|
|심화|HotPlace 관리||X|
|심화|게시판(여행정보 공유) 관리||O|

<span style="color:red">
* 작성된 기능은 반드시 캡쳐되어야 합니다.<br>
* 추가로 구현한 기능을 표에 추가시키세요.
</span>

### 실행화면 캡쳐

#### 회원 관리
![image](/uploads/b3afdaacc8172010061b167013680e71/image.png) <br />

##### 1. 회원 정보 등록
![image](/uploads/f987e0d61f225b2216c9b0b30f465589/image.png)
![image](/uploads/c0b4ec9faf19faa996cbf50894bbe1c4/image.png)
![image](/uploads/02767ea2dac64abd179d90cec91486c3/image.png)

##### 2. 회원 정보 수정
![image](/uploads/392035660615dedb9c01cff87c0f3ec8/image.png)
(전화번호 010-1234-5678 -> 010-4321-9876)
![image](/uploads/e9fe2a98f225231e97694cd397e61d36/image.png)
![image](/uploads/a7e7335e64bbf9d2065d3609578f0884/image.png)

##### 3. 회원 정보 삭제
![image](/uploads/500abee23c5ab50350a7a141297491bf/image.png)
![image](/uploads/4747d86132b00ea1d9ea65e5caabf214/image.png)
![image](/uploads/5ac3bc60779d18e0c28ca4a8467234df/image.png)

##### 4. 회원 정보 검색
![image](/uploads/8c3da6250be11677c38eabd19a6b8465/image.png)
![image](/uploads/f01c7fd9b7839a5c1b4b49bc0e1c5da7/image.png)

##### 5. 로그인/로그아웃
- 로그인 성공
![image](/uploads/895c0fd4a94d15a0e37a01f26b336357/image.png)
![image](/uploads/93d82558f3fa7fcf2c49fb0b7354edbe/image.png)

- 로그인 실패
![image](/uploads/f07ee1afcdf1205c9dfaea2ebaf31b4c/image.png)

- 로그아웃
![image](/uploads/5ddcb0bc1b431bb6c0064ec069b1c227/image.png)
![image](/uploads/d201a4877c37dc773adfb70cc33fce48/image.png)

#### 관광지 정보 관리
![image](/uploads/0d9202ef4c93e9f6d885a67f547d152a/image.png)

##### 1. 전체검색
![image](/uploads/7c251e30ab6972b55b4e8326a78a0e04/image.png)
파라미터를 전혀 넘기지 않고 검색을 할 경우 전체 검색이 됩니다.
![image](/uploads/c8bda42362ee93bae18efcea54907b14/image.png)

##### 2. 상세 조회
![image](/uploads/c8bda42362ee93bae18efcea54907b14/image.png)
table 구조를 수정하여 상세 설명(overview)도 한 테이블에 있게 함으로써 상세조회가 가능하게 했습니다.

##### 3. 지역별 조회
![image](/uploads/f66085a3ac84c28382aee1468f7214eb/image.png)
![image](/uploads/4e60363d4d93be165558a0190d5422f5/image.png)
![image](/uploads/f056db29c6f5ee0f45f76dca4ac02b8f/image.png)
(서울 : 1, 강동구 : 2, 관광지 타입: 입력 x (전체 조회))
![image](/uploads/403f56a9f1f041e09be0ad8b458df0ca/image.png)

##### 4. 관광지 종류별 조회
![image](/uploads/59185c67b23ad1605287eade84ff2590/image.png)
(모든 지역의 음식점 조회)
![image](/uploads/627da20955dba535ce67623e04116729/image.png)

##### 5. 관광지 검색
검색어가 포함되는 주소, 이름에 해당하는 관광지를 출력합니다.
![image](/uploads/8f0f8037729e8e95079839bbb547ffe3/image.png)
![image](/uploads/7f3ef2bac59e810f86bdda0eeead3cff/image.png)
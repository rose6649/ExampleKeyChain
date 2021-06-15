# KeyChain



keyChain은 Apple OS에서 동작하는 응용 프로그램의 보안에 필요한 요소를 저장하는 데 사용되는 암호화된 저장소인 프레임워크입니다. 키체인은 사용자가 직접 제거하지 않는 이상, 앱을 제거해도 남아있을 수 있습니다.



해당 repository는 Apple Document만을 보고 직접 예시를 구현한 것입니다.

> [예시]
>
> ##### 키 체인 아이템:
>
> 토큰값을 저장
>
> ##### 아이템 클래스:
>
> kSecClassGenericPassword
>
> ##### 어트리뷰트:
>
> kSecAttrService = com.keychain
> kdSecAttrAccount = ynwa3690@keychain.com



예시 파일은 key, value 형식으로 저장할 수 있게 구현했습니다. 

다음은 파일 내 기능입니다.

1. ##### 키체인 방식으로 key, value 생성

2. ##### 키체인 방식으로 key, value 업데이트

3. ##### 키체인 방식으로 key, value 삭제

4. ##### 키체인 방식으로 key, value 가져오기 (fetch)
![Swift](https://img.shields.io/badge/Swift-3.0-orange.svg)

# swift-style-guide-myoung
개인적인 Swift언어 스타일 가이드입니다. Pod파일 및 개인 프로젝트등에 적용될 예정입니다.


## Index

- [코드 레이아웃](#코드-레이아웃)
	- [들여쓰기 및 띄어쓰기](#들여쓰기-및-띄어쓰기)
	- [줄바꿈](#줄바꿈)
	- [최대 줄 길이](#최대-줄-길이)
- [참고](#참고) 


## 코드 레이아웃
#### 들여쓰기 및 띄어쓰기

- 들여쓰기는 탭(tab)을 이용합니다.
- 콜론(`:`)을 쓸 경우에는 클론 오른쪽은 항상 공백입니다.
	```swift
	let myName: [String: String]?
	```
- 함수 정의에서 오버로딩 연산자는 첫번째 연산자는 _를 포함해서 함수 호출시 연사자를 생략 합니다
	```swift
    func ** (_ name: String, age: Int)
	```

#### 최대 줄 길이

- 한 줄은 최대 100자로 제한합니다.
    Xcode의 Preferences → Text Editing → Editing의 'Page guide at column' 옵션을 활성화하고 100으로 설정하면 편리합니다. 줄라인 생겨서 보기 편합니다.

## 참고

[Swift 가이드 스타일쉐어](https://github.com/StyleShare/swift-style-guide)

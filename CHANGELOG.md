# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.5] - 2017-07-13
### Added
- 링크 여러개 한번에 열기 기능 추가 [Issue#11](https://github.com/changdoc/naver-vaccine-macro/issues/11).
- 백신 선택 옵션 모더나 추가

## [1.0.4.1] - 2021-07-11
### Changed
- 에러 페이지 노출시 매크로 동작 멈춤 증상 수정 FINAL

## [1.0.4] - 2021-07-11
### Changed
- 에러 페이지 검사 시점 백신 종류 리스트 확인 후에 없을때만 수행되도록 변경
- 에러 페이지 검출 됐을때도 확인을 위해 텔레그램 메시지 발송

## [1.0.3] - 2021-07-10
### Added
- graphql response 처리하여 예약 신청 페이지 이동 편하게 할 수 있도록 목록 생성 기능 추가

### Changed
- 예약 신청 방식 변경 (url 변경하여 페이지 이동 -> 예약 신청 버튼 click event 발생시키는 형태)
- 예약 신청 시도 됐을때 결과를 알 수 없는 상태 (질병 관리 본부 측 timeout)에 텔레그램 메시지 구분하여 전송 되게 수정

### Removed
- 본문에 에러 항목 있을때 새로고침 처리 하는 부분 제거 (오동작 방지 추후 문제 없으면 다시 동작하도록 변경 예정)

## [1.0.2] - 2021-07-09
### Added
- 자동 예약 시작 안내 메시지에 여러 창 떠있을때 새로고침 안내 메시지 추가
- 개인정보 제공동의 input 있으면 자동 checked

### Changed
- error 페이지 노출로 판단되어도 매크로 멈추지 않도록 수정
- 예약 결과 텔레그램 메시지 못보내고 있던 부분 수정

## [1.0.1] - 2021-07-08
### Added
- 백신 선택 옵션 화이자 추가
- test 시 시도 했을 예약 시도 url 디버깅 용으로 추가

### Changed
- test off, 예약 시도 될 때 테스트 메시지 전송 되지 않도록 수정

## [1.0.0] - 2021-06-23
- Initial Version
# ESP32-P4 Web Downloader

## 사용 URL

```
https://htk9998.github.io/ESP32-P4-Web-Downloader/
```

## 사용 방법

1. JIG 를 USB-A 데이터 케이블로 PC 에 연결
2. 위 URL 을 Chrome / Edge 로 접속
3. 별도 전달받은 `FW_Total_V*.bin` 파일 선택
4. Flash offset 확인 (Total 이미지 : `0x0`)
5. Connect & Flash 버튼 클릭 → COM 포트 선택 → 자동 flash
6. 완료 시 JIG 자동 재부팅

## 브라우저 요구사항

| 브라우저 | 지원 |
|:-:|:-:|
| Chrome 89+ | 지원 |
| Edge 89+ | 지원 |
| Opera 76+ | 지원 |
| Firefox | 미지원 (WebSerial 없음) |
| Safari | 미지원 (WebSerial 없음) |

## 기술 스택

- HTML5 + Vanilla JS (프레임워크 없음)
- esptool-js v0.4.5 (CDN : jsdelivr)
- WebSerial API (chip 통신)

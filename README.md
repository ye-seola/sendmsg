# sendmsg

## 프로젝트를 열기 전에 아래 내용을 따라주세요.
1. 링크에서 파일을 다운로드합니다 [android-30.jar 다운로드](https://drive.google.com/drive/folders/17oMwQ0xBcSGn159mgbqxcXXEcneUmnph)
2. 다운로드한 파일을 `app/libs/android-30.jar`에 저장합니다

## 실행
1. `output/sendmsg-{buildType}.dex`를 장치로 옮깁니다.
2. 아래 명령어를 장치에서 실행합니다.
```shell
CLASSPATH=/path/to/sendmsg /system/bin/app_process / io.seola.sendmsg.Main
```
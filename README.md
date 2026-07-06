# ControlBit BLE Gateway

UWB 앵커 보드(PCB v1.2)와 동일 PCB · 동일 케이스를 사용하는 BLE 스캔 게이트웨이 파생 모델의 문서 저장소입니다.

- 문서 사이트: https://wshan1977.github.io/controlbit_bleGateWay/
- 원본 UWB 앵커 문서: https://wshan1977.github.io/controlbit_uwb/

현재는 장치 사양(하드웨어 IO 문서)만 있으며, 펌웨어(BLE 스캔 · MQTT 게이트웨이) 문서는 개발 진행에 따라 추가됩니다.

문서는 `doc/` 아래 Markdown으로 작성하며, `main`에 push하면 GitHub Actions가 MkDocs Material로 빌드해 GitHub Pages에 배포합니다.

로컬 미리보기:

```bash
pip install mkdocs-material
mkdocs serve
```

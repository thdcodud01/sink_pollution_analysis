# 세면대 오염도 자동 분석 시스템 🧼

공공시설 및 상업시설의 세면대 위생 상태를 컴퓨터 비전으로 자동 분석하는 시스템입니다.  
YOLOv8 기반 세면대 탐지 + U-Net 기반 오염 영역 segmentation → 오염도 % 수치화

---

## 🔗 링크
- [Google Drive (Full Colab notebook with results)](드라이브 링크)
- [Run in Colab (Open Notebook)](Colab 링크)

---

## 🚀 실행 방법 (How to Run)

본 프로젝트는 Google Drive와 연동된 데이터가 필요합니다.

### 1️⃣ Google Drive 준비
- `sink_labels.zip` → Google Drive에 업로드 후 `/content/drive/MyDrive/sink_labels/` 경로에 압축 해제
- `SmartSan_Project.zip` → Google Drive에 업로드 후 `/content/drive/MyDrive/SmartSan_Project/` 경로에 압축 해제

### 2️⃣ Colab 노트북 열기
- [Run in Colab (Open Notebook)](Colab 링크)

### 3️⃣ 실행
- Colab 노트북 첫 번째 Cell에서 Google Drive mount 코드 실행
- 이후 순서대로 코드 셀 실행

---

## 📚 기술 스택

- Python
- PyTorch
- YOLOv8
- U-Net
- Albumentations
- LabelMe

---

## 📝 참고
- 본 프로젝트는 AI융합학과 컴퓨터비전 프로젝트로 진행되었습니다.

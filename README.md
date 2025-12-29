# Medical AI Workbook

실전 의료 데이터 기반 머신러닝 및 임상 데이터 분석 학습 과정

배포 사이트: https://leejoohyunn.github.io/medical-ai-workbook/

## 개요

본 워크북은 의료 인공지능 학습을 위한 체계적인 커리큘럼을 제공합니다. PhysioNet, UCI ML Repository, Kaggle, NIH 등에서 제공하는 실제 임상 데이터를 활용하여 기초부터 고급 응용까지 단계적으로 학습할 수 있도록 설계되었습니다.

## 커리큘럼 구성

### Level 2: Intermediate Medical AI (20개 워크북)
- **Module 2-1**: 전자건강기록(EHR) 및 테이블 데이터 분석 (4개)
- **Module 2-2**: 시계열 생체신호 분석 (4개)
- **Module 2-3**: 의료 영상 분석 기초 (4개)
- **Module 2-4**: 의료 텍스트 분석 기초 (4개)
- **Module 2-5**: 멀티모달 분석 기초 (4개)

### Level 3: Advanced Medical AI (10개 워크북)
- **Module 3-1**: 생존 분석 및 시계열 예측 (2개)
- **Module 3-2**: 고급 생체신호 딥러닝 (2개)
- **Module 3-3**: 의료 영상 딥러닝 (2개)
- **Module 3-4**: 의료 텍스트 딥러닝 (2개)
- **Module 3-5**: 고급 멀티모달 딥러닝 (2개)

## 기술 스택

- **Framework**: Quarto
- **Language**: Python
- **Libraries**: NumPy, Pandas, Scikit-learn, PyTorch/TensorFlow
- **Deployment**: GitHub Pages

## 로컬 개발

### 요구사항
- Python 3.8+
- Quarto 1.3+
- Node.js (StaticCrypt용)

### 설치 및 실행

```bash
# 저장소 클론
git clone https://github.com/YOUR_USERNAME/medical-ai-workbook.git
cd medical-ai-workbook

# Quarto 미리보기
quarto preview
```

### 빌드 및 배포

```bash
# 사이트 빌드
quarto render

# GitHub Pages에 배포 (자동)
git add .
git commit -m "Update site"
git push
```

## 라이센스

본 프로젝트의 모든 내용은 교육 목적으로 제공됩니다.

## 기여

이슈 및 개선 제안은 GitHub Issues를 통해 제출해주세요.

# jadx-pest-ai

JADX 제주 농업 병해충 예측 시스템 — 신규 4종 모형 개발 (Colab 기반)

## 대상 종
- 네눈쑥가지나방 (Ascotis selenaria)
- 왕담배나방 (Helicoverpa armigera)
- 파밤나방 (Spodoptera exigua)
- 조팝나무진딧물 (Aphis spiraecola)

## 폴더 구조
```
jadx-pest-ai/
├── notebooks/          # Colab 노트북
│   ├── step1_weather.ipynb       # 기상 데이터 수집
│   ├── step3_validation.ipynb    # 데이터 검증
│   ├── step4_model.ipynb         # 모델 실행
│   └── step5_visualization.ipynb # 결과 시각화
├── src/
│   └── model.py        # 모델 함수 모듈
├── data/               # 데이터 파일 (gitignore)
└── README.md
```

## 참고 논문
- Choi & Kim 2014 (Crop Protection 66:72-79)
- Choi & Kim 2016 (JEE 109(3):1267-1272)

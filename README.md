# 보고, 읽고, 설명하는 딥러닝 — 실습 노트북

『보고, 읽고, 설명하는 딥러닝 — Colab에서 직접 만들며 배우는 딥러닝 응용』(신영학 지음)의 장별 실습 노트북입니다.

아래 표의 **Colab에서 열기**를 누르면 설치 없이 브라우저에서 바로 실행할 수 있습니다. 코드를 바꿔 보려면 Colab 메뉴 [파일] → [Drive에 사본 저장]으로 내 드라이브에 복사한 뒤 실행하세요. 4·5·7·10~13장은 [런타임] → [런타임 유형 변경]에서 T4 GPU를 고르면 빠릅니다.

| 장 | 노트북 | Colab |
|---|---|---|
| 1장 심층 신경망의 원리 | [`ch01_dnn_basics.ipynb`](notebooks/ch01_dnn_basics.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch01_dnn_basics.ipynb) |
| 2장 Keras로 신경망 구현하기 | [`ch02_keras_basics.ipynb`](notebooks/ch02_keras_basics.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch02_keras_basics.ipynb) |
| 3장 합성곱 신경망(CNN) | [`ch03_cnn_basics.ipynb`](notebooks/ch03_cnn_basics.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch03_cnn_basics.ipynb) |
| 4장 대표 CNN 아키텍처와 전이학습 | [`ch04_transfer_learning.ipynb`](notebooks/ch04_transfer_learning.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch04_transfer_learning.ipynb) |
| 5장 설명 가능한 AI — 모델은 어디를 보았나 | [`ch05_xai.ipynb`](notebooks/ch05_xai.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch05_xai.ipynb) |
| 6장 모델을 어떻게 평가하는가 — 분류 평가 지표 | [`ch06_metrics.ipynb`](notebooks/ch06_metrics.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch06_metrics.ipynb) |
| 7장 영상 분할 — U-Net으로 대장 용종 분할하기 | [`ch07_unet.ipynb`](notebooks/ch07_unet.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch07_unet.ipynb) |
| 7장 객체 검출 — YOLO11 커스텀 학습 | [`ch07_yolo.ipynb`](notebooks/ch07_yolo.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch07_yolo.ipynb) |
| 8장 순환 신경망 — RNN과 LSTM | [`ch08_rnn_lstm.ipynb`](notebooks/ch08_rnn_lstm.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch08_rnn_lstm.ipynb) |
| 9장 딥러닝 자연어 처리 | [`ch09_nlp.ipynb`](notebooks/ch09_nlp.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch09_nlp.ipynb) |
| 10장 어텐션과 트랜스포머 | [`ch10_attention_transformer.ipynb`](notebooks/ch10_attention_transformer.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch10_attention_transformer.ipynb) |
| 11장 사전학습 언어 모델 | [`ch11_pretrained_lm.ipynb`](notebooks/ch11_pretrained_lm.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch11_pretrained_lm.ipynb) |
| 12장 SAM | [`ch12_sam.ipynb`](notebooks/ch12_sam.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch12_sam.ipynb) |
| 13장 내 모델을 웹 데모로 | [`ch13_gradio.ipynb`](notebooks/ch13_gradio.ipynb) | [Colab에서 열기](https://colab.research.google.com/github/myway0101/see-read-explain-dl/blob/main/notebooks/ch13_gradio.ipynb) |

## 실행 환경

2026년 10~11월 Google Colab(Python 3.13, TensorFlow 2.21, Keras 3.15)에서 실행을 확인했습니다. 라이브러리 버전이 바뀌어 결과 숫자가 책과 조금 다를 수 있습니다. 자세한 내용은 책의 부록 A·B를 참고하세요.

## 데이터 출처

실습 데이터는 각 노트북에서 원래 배포처에서 내려받습니다. MNIST·Fashion-MNIST(케라스 내장), Kaggle Cats and Dogs(Microsoft), Kvasir-SEG(Jha 등, 2020, 연구·교육 목적), Aquarium Dataset(Roboflow, CC BY 4.0), 영어–스페인어 문장 쌍(TensorFlow 예제 데이터) 등의 이용 조건은 각 배포처를 따릅니다.

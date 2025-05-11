

# StableDiffusion

이 프로젝트는 Stable Diffusion 모델을 활용하여 텍스트 기반 이미지 생성 및 얼굴 복원 기능을 제공하는 Jupyter Notebook 기반의 실험 환경입니다. AUTOMATIC1111 Web UI를 활용한 빠른 이미지 생성, 프롬프트 실험, DreamBooth 기반 모델 파인튜닝 등 다양한 기능을 포함하고 있습니다.

## 📁 프로젝트 구성

* **fast\_stable\_diffusion\_AUTOMATIC1111.ipynb**: AUTOMATIC1111 Web UI를 활용하여 빠르게 Stable Diffusion을 실행하는 노트북입니다.
* **face\_ai\_test.ipynb**: 얼굴 복원 기능을 테스트하는 노트북입니다.
* **prompt\_ex.ipynb**: 다양한 프롬프트를 실험하여 이미지 생성 결과를 비교하는 노트북입니다.
* **prompt\_trainning.ipynb**: 프롬프트 기반 모델 파인튜닝을 위한 노트북입니다.

## 🚀 설치 및 실행 방법

1. 리포지토리 클론:

   ```bash
   git clone https://github.com/hyunaeee/StableDiffusion.git
   cd StableDiffusion
   ```



2. 필요한 패키지 설치:

   ```bash
   pip install -r requirements.txt
   ```



3. Jupyter Notebook 실행:

   ```bash
   jupyter notebook
   ```



4. 원하는 노트북 파일을 열어 실행합니다.


## 📌 참고 사항

* AUTOMATIC1111 Web UI를 활용한 이미지 생성은 `fast_stable_diffusion_AUTOMATIC1111.ipynb`에서 확인할 수 있습니다.
* 얼굴 복원 기능은 `face_ai_test.ipynb`에서 테스트할 수 있습니다.
* 프롬프트 실험 및 파인튜닝은 각각 `prompt_ex.ipynb`와 `prompt_trainning.ipynb`에서 수행할 수 있습니다.


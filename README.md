# MultiLabel-foodimg-classification

식단관리 서비스 앱인 ‘스프린트’기업을 주제로 기획한 프로젝트입니다.

수행할 주제는 음식 이미지 분류로써 초기에는 식단 사진의 각 개체를 구분(예: 햄버거세트면, 햄버거, 감자튀김, 음료를 구분)하여 분류해주는 프로젝트를 진행하고자 했으나, 여러 측면을 고려하여 해당 이미지를 주면 이것이 건강식단 범주의 어떤 종류인지를 구분하게 단순화 하였습니다.

동작 예는 다음과 같습니다.
input 으로 닭가슴살 샐러드 사진이 들어간다면, output = [ ‘닭가슴살’, ‘건강식단’,’샐러드’] 식으로 각 클래스에 따른 확률을 출력하게 됩니다.

생성할 모델에 대한 이해와 모델에 어떤 데이터가 들어가야하는지 그리고 데이터에 대한 전처리는 어떻게 이뤄져야하는지를 이해하고 수행하는 과정을 기록하였습니다.

자세한 기록과 참고한 자료를 보고 싶으시다면 [개인노션페이지](https://obvious-rock-3e1.notion.site/b407fc13492740c78af973e2e104e56e?v=9245d1e1067e4d2092a536e0929324aa)에서 보실 수 있습니다.

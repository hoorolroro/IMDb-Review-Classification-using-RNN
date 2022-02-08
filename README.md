# RNN 모델을 이용한 영화 평점 예측
## RNN(Recurrent neural network)  
● RNN 모델은 이미지보다는 문장과 같은 sequential data에 강하다.  

<img src="https://user-images.githubusercontent.com/98728682/152925435-d06a59a8-08da-478f-866b-ead91b657a84.jpg" width="480" height="230">

## RNN의 구조
<img src="https://user-images.githubusercontent.com/98728682/152928257-b2d77a00-25a9-4e63-a5e9-025033522c88.png" width="150" height="230"><img src="https://user-images.githubusercontent.com/98728682/152928367-fdc197f5-8728-409c-bcc3-3222f1458136.png" width="480" height="230">  

● RNN은 추가된 input(xt)과 과거의 정보(ht-1)를 조합해, 새로운 정보(ht)를 생성하는 구조이다.  

● Task에 따라서 yt가 필요한 경우와 필요하지 않은 경우가 있다.  

● Input과 이전 state를 선형 변환하여 결합한 후 activation에 적용한다.  

● Activation function은 주로 tanh를 사용한다. 
<img src="https://user-images.githubusercontent.com/98728682/152931989-1d46dbc6-7fdb-47d9-9e31-ffb054b8a3b4.png" width="480" height="100">

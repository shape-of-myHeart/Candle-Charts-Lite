# Candle.js
<p>
Candle.js 는 캔들차트를 그리기 위한 라이브러리입니다.<br/>
캔들차트가 주고, 보조지표에 필요한 다른 차트타입도 사용할 수 있습니다.
</p>
<p>
지금까지 캔들차트는 다른 차트라이브러리의 일부기능으로, 부가적으로 따라오는 경우가 많았습니다.<br/>
이는 캔들차트를 위해 필요없는 로직들을 불러오기 때문에, 속도나 용량에 큰 문제를 야기했습니다.
</p>
<p>
게다가 다른 자바스크립트 차트 라이브러리는 대부분 svg로 구현되어있지만<br/>
캔들차트처럼 데이터량이 많은 차트를 svg로 그릴경우 심각한 속도저하가 일어납니다.
</p>
<p>
Candle.js의 장점은
쓸 때 없는 로직들을 불러오지 않아, 속도나 용량 측면에서 매우 가볍고,<br/>
많은 데이터량을 출력하는데 어울리지않는 svg 대신 canvas 를 이용하여 렌더링 속도를 향상시켰습니다.
</p>
<p>
Candle.js 의 지향점<br/>
  <ol>
    <li>속도와 용량이 가벼워야한다.</li>
    <li>빌드환경 또한 가벼워야 한다.</li>
    <li>사용자에게 너무 많은 자유도를 주지않는다.</li>
    <li>사용자의 입력값에 대한 타입체크를 피한다.</li>
  </ol>
</p>

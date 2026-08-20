# 소형항온챔버 히팅 기능 문제 시 점검

> **SINOPRO** · 교육 자료 · 2026. 08. 20.

{% hint style="info" %}
본 자료는 챔버(항온) 장비의 점검 방법과 컴프레셔 교체 작업 절차를 설명하는 교육 자료입니다.&#x20;

브레이징·냉매 취급 작업이 포함되므로, 각 단계의 주의사항을 반드시 확인한 후 작업을 진행하세요.
{% endhint %}

## 안전 수칙

1. 판넬을 열기 전, 손이 젖어 있으면 안됩니다.
2. **전원 케이블이 분리된 상태를 확인**한 뒤 판넬을 엽니다.
3. 테스터기 핀은 양손에 하나씩 잡고, 끝 부분은 금속 재질이므로 만지지 않습니다.
4. **측정하려는 단자 두 곳에만 닿게** 합니다. 옆 단자나 금속재질 프레임  등에 스치지 않게 합니다.



## 준비물

<table><thead><tr><th width="75" align="center">번호</th><th>부품</th></tr></thead><tbody><tr><td align="center">1</td><td>십자 드라이버 또는 전동 드릴</td></tr><tr><td align="center">2</td><td>전압 테스터기 (멀티미터)</td></tr><tr><td align="center">3</td><td>절연장갑</td></tr><tr><td align="center">4</td><td>절연테이프</td></tr></tbody></table>

## 점검 절차

{% stepper %}
{% step %}
## 증상 확인

설정 온도를 셋팅후 챔버 내부 온도가 상승하지 않는지 확인합니다.

디스플레이는 정상적으로 출력되지만 온도가 올라가지 않아 미달되어 유지될 경우 파워서플라이 고장을 의심합니다.
{% endstep %}

{% step %}
## 히터 동작 확인

터치패널에서 설정 온도를 현재 온도보다 높게 입력합니다.

일정 시간 경과 후 내부 온도가 상승하는지 확인하고 온도가 올라가지 못할 경우 다음 단계로 진행합니다.
{% endstep %}

{% step %}
## 판넬 개방

전원 케이블을 분리한 상태에서 십자 드라이버로 상부 판넬(커버)을 분리합니다.
{% endstep %}

{% step %}
## 점검 위치 확인

파워서플라이와 제어 보드 위치를 확인한 후, 전원 케이블을 다시 연결하고 전원 버튼을 ON 합니다.
{% endstep %}

{% step %}
## 입력 전압 측정 (AC)

테스터기를 ACV로 설정하고 파워서플라이 입력부를 측정합니다. (빨간색, 파란색케이블)

&#x20;220V 측정 시 정상입니다.
{% endstep %}

{% step %}
<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
## 신호전압 측정 (DC)

테스터기를 DCV로 전환하고 5V 케이블과 신호케이블을(노란색) 측정합니다.

챔버가 running일 경우에는 5v, stand by 상태일 경우에는 0v (신호가 가지않음)가 정상입니다.


{% endstep %}

{% step %}
<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>


{% endstep %}

{% step %}
## 출력 전압 측정 (DC)

파워서플라이 출력부를 측정합니다. (갈색, 파란색케이블) 5V 측정 시 정상입니다.

0V 측정 시 파워서플라이 출력에 이상이 있으며 고장이라고 판단할 수 있습니다.
{% endstep %}

{% step %}
<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>


{% endstep %}

{% step %}
## 파워서플라이 교체 작업

전원을 OFF 한 뒤, 전원 케이블을 분리합니다.

고정 볼트를 제거합니다.

파워서플라이의 배선 배치 상태를 촬영하여 기록합니다. (교체 후 배선 연결할 때 참고용으로 필수입니다.)

파워서플라이 교체 후 다시 고정볼트로 고정합니다.

촬영해 놓은 배선 배치를 참고하여 그대로 체결합니다.

<figure><img src=".gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
## 테스트/모니터링

전원 케이블을 연결한 뒤 전원을 ON 합니다.

설정 온도를 희망하는 온도로 맞추고 온도 유지 테스트를 진행합니다.

이후 장시간 유지 확인 시 조치 완료로 판단합니다.
{% endstep %}
{% endstepper %}


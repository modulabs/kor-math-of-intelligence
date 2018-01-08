# Intro_to_the_Math_of_intelligence
이 코드는 Siraj Raval의 강의인 The Math of Intelligence를 한글화한 것입니다.

## Overview  
이 코드에 해당하는 [동영상](https://youtu.be/xRJCOz3AfYY)은 Siraj Raval이 제작해서 업로드한 것입니다. 동영상에서 활용된 데이터는 자전거로 간 거리 대비 칼로리 소모에 관한 것입니다. 이제 Gradient descent(경사하강법)을 이용하여, 자전거 이동거리에 따른 칼로리 소모를 예측하는 직선을 만들 것입니다. 동영상에서는 Gradient descent에 필요한 learning rate(학습률)에 대해서는 얘기하지는 않습니다. 우린 아직 준비가 덜됬죠. (나중에 다룰 겁니다.)

아래에 도움이 될만한 링크들이 있습니다.

#### Gradient descent visualization
https://raw.githubusercontent.com/mattnedrich/GradientDescentExample/master/gradient_descent_example.gif

#### Sum of squared distances formula (to calculate our error)
https://spin.atomicobject.com/wp-content/uploads/linear_regression_error1.png

#### Partial derivative with respect to b and m (to perform gradient descent)
https://spin.atomicobject.com/wp-content/uploads/linear_regression_gradient1.png

## Dependencies

* numpy

Python 2와 3에서 이 코드는 잘 작동합니다. [pip](https://pip.pypa.io/en/stable/)을 이용해서 numpy를 설치하세요.

## Usage

``python3 demo.py``을 실행시키면 다음의 결과를 볼 수 있습니다.
   ```
Starting gradient descent at b = 0, m = 0, error = 5565.107834483211
Running...
After 1000 iterations b = 0.08893651993741346, m = 1.4777440851894448, error = 112.61481011613473
   ```

## Credits

Credits for this code go to [mattnedrich](https://github.com/mattnedrich). I've merely created a wrapper to get people started. 
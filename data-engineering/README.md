# Split Brain 이란?

시스템의 두 부분 이상이 독립적으로 진행되어 시스템이 일관되지 않게 동작하는 것을 말한다.

분산 시스템에서 마스터-슬레이브 상태에서 네트워크 이상으로 인해 슬레이브는 마스터가 이상이 있다고 판단한다.
때로는 맞을 수도 있고 때로는 오탐일 수도 있다. 만약 잘못된 판단임에도 슬레이브 중 하나가 마스터로 선출이 되면 두 개의 마스터가 존재하게 된다. 이런 경우를 Split Brain 스플릿 브레인이라고 부른다.
# Noonsatae_Spec

### TBD 아직 가야할 길이 XXXXXXXXX나게 멂멂멂멂멂멂 와우!!

## index

- Abstract
- 1. Introduction
- 2. Preliminaries
- 3. Network
- 4. Consensus (Difficulty)
- 5. Attack Scenario
- 6. Conclusion


#### Difficulty 
Staking 건 양에 따라서 바뀌는 난이도 
저 사람의 난이도도 알 수가 있는 상태 
모두의 난이도가 달라도 다른 사람이 문제를 똑바로 풀었는지는 확인할 수 있음 
Account - Balance - Nonce 
Transaction 이 들어오면 snapshot hash 가 지속적으로 바뀔 것 
Snapshot 이 나오는 주기를 알 수가 있음 

분기가 일어나면 weight 가 가장 무거운 것을 선택하라고 권고할거임 
이렇게 유도하면 제일 무거운 것이 자연스럽게 main snapshot 이 될 것
Snapshot 의 무게는 포함되어 있는 transaction들의 무게들의 합 
상대방의 snapshot weight 를 검증할 수 없음. 
하지만 snapshot 의 수수료의 총합은 검증할 수 있음. (이게 아닐수도, weight는 안되는 것) 이렇게 되면 위변조가 안됨 

light vs light // heavy vs light // heavy vs heavy 

이렇게 되면, snapshot 을 찍는 주기를 맞출 수 있음

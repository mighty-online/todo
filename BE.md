#### 1/6

방 관리 {
  
 
  방을 GR 보내기
  
  
}

FE와 상호작용 {

  받는거 {
  
    1. 대기 시그널 받기
    
    2. 수 전달받기
  
  }
  
  주는거 {
  
    1. UI Control 전달 (GR로부터 받아서)
  
  }
  
}


나는 방 안의 상태를 '철저히' 모르게 짜야 한다.


GR과 상호작용 {

  받는거 {
  
    1. 새로운 방
    
    2. UI Control
    
    3. is AI Called?
    
    4. Game Over Signal + Reward
  
  }
  
  
  할거 {
  
    1. AI 신호 판단 후 {
    
      AI 라면 : perspectivce 전달
      
    } -> UI Control
   
  }
  
  주는거 {
  
    1. 시작 request
    
    2. player가 뭘 요청했는지 ( FE로 부터 받아서 다시 전달)
    
  }
  
}

- [ ] Server Class, Container(GR한테 받아오는거) Class
- [ ] 
- [ ] 

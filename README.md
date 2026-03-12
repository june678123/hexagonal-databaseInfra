# hexagonal-databaseInfra


이 repo는 hexagonal 아키텍처를 구현한 어플리케이션에 대한 repo입니다.

이 프로젝트는,
인프런의, han jeong heon님의 Microservice 구현 (with EDA,Hexagonal, DDD)강의를 보며,
거기서 나오는 hexagonal 서비스 코드를 보고, java와 kotlin 2가지 언어를 쓰는 버전으로 해당 서비스 코드를 구현하면서 진행되었습니다.

그 이후에(여기서부터는 제가 개인적으로 클로드 코드를 활용하며 진행하였습니다.), 
도메인 계층에 있던 jpa 의존성을 framework 계층으로 이동시켜 포트에 대한 의존성 격리를 시키는 헥사고널 원칙을 적용시켰습니다. 
그후 헥사고널 아키텍처의 장점인 인프라에 의존적이지 않은 비즈니스 로직 이라는 장점을 살리기 위해, framework 게층에 jpa 뿐만 아니라 reactive mongo 또한 추가시키고, 설정파일의 프로필 설정만으로 두가지 데이터베이스 중 하나를 선택하여 사용할 수 있도록 하였습니다.
또한 순수 비즈니스 로직에 대한 테스트 파일들을 생성시켜, 비즈니스 로직에 대해 인프라 독립적인 검증환경아 구축되게 하였습니다.

## Notice & Copyright
Copyright © 2026 june678123. All rights reserved.
이 프로젝트는 학습 및 포트폴리오 용도로 제작되었으며, 무단 복제 및 배포를 금합니다.
본 프로젝트의 도메인 로직 및 시나리오는 인프런 'Microservice 구현 (with EDA,Hexagonal, DDD)/han jeong heon'의 강의 콘텐츠를 바탕으로 작성되었습니다. 원저작권자의 요청이 있을 경우 해당 코드는 즉시 비공개 처리될 수 있음을 밝힙니다

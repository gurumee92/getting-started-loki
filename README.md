# 구르미의 Grafana Loki 시작하기

## 목차

### 1부 로키란 무엇인가?

1. 로키란 무엇인가?
2. 로키 맛보기 (PPLG 스택)

### 2부 로키 컴포넌트 파헤치기

1. 로키 컴포넌트 (1) Distributor 
2. 로키 컴포넌트 (2) Querier 
3. 로키 컴포넌트 (3) Query Frontend 
4. 로키 컴포넌트 (4) Ingester
5. 로키 컴포넌트 (5) Ruler
6. 로키 컴포넌트 (6) Alertmanager
7. 로키 컴포넌트 (7) Compactor

### 3부 LogQL

1. LogQL 사용하기 (1) Log Queries
2. LogQL 사용하기 (2) Metric Queries
3. LogQL 사용하기 (3) 기타 기능
4. LogQL 사용하기 (5) Best Practice

### 4부 로키 클라이언트

1. 로키 클라이언트 (1) Promtail
2. 로키 클라이언트 (2) Fluentbit
3. 로키 클라이언트 (3) Fluentd
4. 로키 클라이언트 (4) Logstash
5. 로키 클라이언트 (5) AWS EC2
6. 로키 클라이언트 (6) AWS ECS
7. 로키 클라이언트 (7) AWS EKS
8. 로키 클라이언트 (8) AWS Lambda

### 5부 당신의 행복을 위한 7가지 조언

1. 더 쉬운 배포를 위해 당장 Kubernetes와 Helm을 도입하라.
2. 쿼리 성능 향상을 위해서 Memcached를 도입하라.
3. 시스템 안정성을 위해서 Kafka 도입을 고려하라. (Agent 통합, Back Pressure 조절, 로그 이중화 등)
4. Prometheus를 이용해서 반드시 모니터링하라.
5. Elastic 스택보다 좋을 거라는 생각을 버려라.
6. Grafana Loki는 오픈 소스임을 명심하자. (1) pprof를 이용한 프로파일링
7. Grafana Loki는 오픈 소스임을 명심하자. (2) delve를 이용한 디버깅

# 안녕하세요! 👋 신형석입니다

> Java/Spring 기반 백엔드 개발과 배포/운영 자동화까지 연결하는 백엔드 엔지니어입니다.

Spring Boot 기반 API 개발 경험과 함께, AWS EC2 환경에서 Docker Compose + Nginx + GitLab CI를 활용한 CI/CD 파이프라인 구축 및 Blue/Green 무중단 배포(/actuator/health 헬스체크) 경험을 보유하고 있습니다.  
기능 구현에 그치지 않고, 운영 환경에서 안정적으로 배포·관측·운영 가능한 형태로 전달하는 것을 지향합니다.

## 🛠️ 기술 스택

Languages:  Java
Frameworks: Spring Boot, JPA, MyBatis
DB/Cache:   MySQL, Redis
DevOps:     AWS EC2, Docker, Docker Compose, Nginx, GitLab CI/CD
Obs:        Prometheus, Grafana, Loki, Promtail, Nginx Access Log
Focus:      Backend API, CI/CD, Blue/Green Deployment, 운영 안정성

### 💻 핵심 역량
- **Backend API**: Spring Boot 기반 API 설계/구현, 데이터 흐름 설계(외부 API 연동 포함)
- **DB/Cache**: MySQL 스키마/조회 설계, Redis 활용 경험
- **CI/CD**: GitLab CI(test/deploy) 파이프라인 구성 및 배포 자동화
- **무중단 배포**: Docker Compose + Nginx 포트 스위칭 기반 Blue/Green 배포, `/actuator/health` 헬스체크 적용
- **Observability**: Prometheus/Grafana 및 Nginx 로그 기반 운영 점검, Loki/Promtail 구성 경험

## 🧩 프로젝트 하이라이트

### 📈 주식 게임 서비스 (6인) — 인프라/배포 주 담당, 백엔드 일부 지원
- GitLab CI(test/deploy) 구축 및 master push 시 배포 트리거 rules 적용
- EC2로 소스/구성 동기화(rsync/scp) 후 `deploy.sh` 실행으로 배포 자동화
- Blue/Green 무중단 배포 구현(backend-blue/green 교대 기동 → `/actuator/health` 통과 후 Nginx reload 트래픽 전환)
- Prometheus/Grafana 및 Nginx access log 기반 운영 점검, CPU 사용량 확인
- 개발/배포 DB 분리 및 SSH 터널링 기반 로컬→EC2 내부 DB 접속(Workbench) 가이드 문서화/공유

### 🧳 여행 대시보드(Trip-Board, 2인) — 백엔드/DB/API
- TourAPI 연동: DB 우선 조회 → 미존재 시 외부 API 호출 → DB 저장 후 응답
- `content_id` 존재 체크 후 insert로 중복 저장 방지
- 출발/도착 지역, 여행 기간 조건 기반 조회 API 구현(MySQL/MyBatis)

## 💼 경력

**레미라움** — 게임 클라이언트/시스템(데이터 기반 밸런싱) _(2024.03 ~ 2025.04)_
- 전투력 산정 모델 설계 및 시뮬레이션 검증을 통한 지표 적합도 개선
- Orange3 기반 재화 로그 분석 및 경제 밸런싱(구간별 증가율 변동폭 기반 튜닝)

## 🎓 학력
**경북대학교** - 컴퓨터학부 졸업

## 📊 GitHub 통계
![GitHub stats](https://github-readme-stats.vercel.app/api?username=queenanemone&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=queenanemone&layout=compact&theme=tokyonight)

## 📫 연락처
- **이메일**: chaos1375@naver.com
- **GitHub**: [@queenanemone](https://github.com/queenanemone)
- **블로그**: https://velog.io/@shinhs9902/posts
- **위치**: 대전광역시

---

⭐️ **"운영 가능한 형태로 서비스를 전달하는 백엔드 엔지니어를 지향합니다."**

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=queenanemone.queenanemone)

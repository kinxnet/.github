# KINX Cloud Development Team Organization-wide GitHub Default Configuration

이 저장소는 `kinxnet` GitHub 조직 전체의 기본 템플릿과 공통 정책을 관리하는 조직 기본 저장소입니다.

## 포함된 기본 템플릿

- **Issue Forms (`.github/ISSUE_TEMPLATE/`)**:
  - `feature.yml`: 신규기능 / 고도화
  - `bug.yml`: 일반 결함 / 버그
  - `incident.yml`: 운영 장애 / 핫픽스 (MTTR 및 변경 실패율 추적용, DORA 프레임워크 참조)
  - `policy.yml`: 기획 / 정책 / 아키텍처
  - `config.yml`: 빈 이슈 생성 제한 및 피드백 링크
- **Pull Request Template (`.github/pull_request_template.md`)**:
  - `Closes #이슈번호` 필수 연결 (엔지니어링 변경 리드타임 측정용)
  - 작업 유형 및 변경 Layer 명시
  - PR 크기 상한 및 AI 어시스턴트 활용 여부 체크리스트

## 운영 기준

- 상세 표준: [kinxnet/deployment-process-standard-draft](https://github.com/kinxnet/deployment-process-standard-draft)

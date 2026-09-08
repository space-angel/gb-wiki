# ADR 목록과 효력

**로컬 원문 기준: Accepted 11건, Proposed 4건.** 2026-09-08 파일 상태를 정리했으며 Notion의 현재 승인 상태를 새로 조회한 결과는 아닙니다.

| ADR | 내용·원문 | 상태 | 확인되는 규칙·제안 | 함께 볼 경계 |
|---|---|---|---|---|
| ADR-1 | [이해도 정의](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-01_%EC%9D%B4%ED%95%B4%EB%8F%84%EC%A0%95%EC%9D%98.md) | Accepted | 인식 변화량, 수치 비노출, 플레이어 스탯 강화 금지 | ADR-9가 출력 범위 일부 개정 |
| ADR-2 | [이해도 내부 표현](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-02_%EC%9D%B4%ED%95%B4%EB%8F%84%EB%82%B4%EB%B6%80%ED%91%9C%ED%98%84.md) | Accepted | O→A→V→R 4개 boolean과 순서 의존 | 구체 트리거·축별 범위는 미결 |
| ADR-3 | [아이템 위계](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-03_%EC%95%84%EC%9D%B4%ED%85%9C%EC%9C%84%EA%B3%84.md) | Accepted | 핵심·보조 2등급, 핵심 3개, O 기존 조건 | ADR-15가 보조 수량만 개정 |
| ADR-4 | [가설 선택지](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-04_%EA%B0%80%EC%84%A4%EC%84%A0%ED%83%9D%EC%A7%80.md) | Accepted | 정답 1 + 오답 2의 3지선다 | 실제 가설·오답 콘텐츠는 기획 중 |
| ADR-5 | [재구성 보드](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-05_%EC%9E%AC%EA%B5%AC%EC%84%B1%EB%B3%B4%EB%93%9C.md) | Accepted | 메인·보조·진술·추리의 4슬롯 | 각 조합·판정과 콘텐츠 연결은 별도 |
| ADR-6 | [A/V 핵심 진술자 분리](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-06_AV%EB%8B%A8%EA%B3%84NPC%EB%B6%84%EB%A6%AC.md) | Accepted | A/V 핵심 진술자 분리, 각 최소 2명 | NPC 배정 잠정, R 관련 참조 공백 |
| ADR-7 | [사령세계 구조](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-07_%EC%82%AC%EB%A0%B9%EC%84%B8%EA%B3%84%EA%B5%AC%EC%A1%B0.md) | Accepted | 메트로배니아, 탐색과 보스방 분리 | 실제 맵·개방 순서 미결 |
| ADR-8 | [전투 톤](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-08_%EC%A0%84%ED%88%AC%ED%86%A4.md) | Accepted | 가벼운 톤, 방어는 회피, 패링·가드 제외 | 실제 패턴·전투 결과 기획 중 |
| ADR-9 | [이해도 출력 범위](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-09_%EC%9D%B4%ED%95%B4%EB%8F%84%EC%B6%9C%EB%A0%A5%EC%A0%81%EC%9A%A9%EB%B2%94%EC%9C%84.md) | Accepted | 보스 가시성·종결, 잡몹 영향 제외 | 시각 표현 수단 미결 |
| ADR-10 | [게임 시점](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-10_%EA%B2%8C%EC%9E%84%EC%8B%9C%EC%A0%90.md) | Accepted | 챕터1 현실 사이드뷰·사령 탑다운뷰 | 다른 챕터 적용·실제 에셋 별도 |
| ADR-11 | [공간 개방 규칙](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-11_%EC%82%AC%EB%A0%B9%EC%84%B8%EA%B3%84%EA%B3%B5%EA%B0%84%EA%B0%9C%EB%B0%A9%EA%B7%9C%EC%B9%99.md) | Proposed | 메인 유품 게이트·순차 획득 제안 | 스토리의 동시 노출안과 충돌 |
| ADR-12 | [이해도 판정 규칙](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-12_%EC%9D%B4%ED%95%B4%EB%8F%84%ED%8C%90%EC%A0%95%EA%B7%9C%EC%B9%99.md) | Proposed | 보조 N개·유품 제시·회상·최종 보드 제안 | O·A/V/R 매핑 정합성 필요 |
| ADR-13 | [3계층 시스템 분리](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-13_3%EA%B3%84%EC%B8%B5%EC%8B%9C%EC%8A%A4%ED%85%9C%EB%B6%84%EB%A6%AC.md) | Proposed | 인벤토리·플래그·컷씬 참조 방향 제안 | 단서별 대화 공개와의 관계 검토 |
| ADR-14 | [오답 처리 시스템](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-14_%EC%98%A4%EB%8B%B5%EC%B2%98%EB%A6%AC%EC%8B%9C%EC%8A%A4%ED%85%9C.md) | Proposed | 무제한 재시도·배치만 리셋·실패 피드백 없음 제안 | 판매 규칙과 구분, 실제 UI 미정 |
| ADR-15 | [보조유품 수량 개정](https://github.com/space-angel/gb-wiki/blob/e4e7a0870f9647974c11269d84a59b7fe1d59f2a/raw/00_%EC%BB%B4%ED%94%8C%EB%9D%BC%EC%9D%B4%EC%96%B8%EC%8A%A4/ADR/ADR-15_%EB%B3%B4%EC%A1%B0%EC%95%84%EC%9D%B4%ED%85%9C%EC%88%98%EB%9F%89%EA%B0%9C%EC%A0%95.md) | Accepted | 보조 6개, 조사축당 2개, N≤6 | N 자체와 O 정의는 확정하지 않음 |

## 개정 관계

- ADR-9는 ADR-1의 출력 중 잡몹 영향을 제외했습니다. 현재 출력 범위를 옛 3종으로 읽지 않습니다.
- ADR-15는 ADR-3의 보조 수량을 10~12개에서 6개로 바꿨습니다. 현재 총 유품 수는 핵심 3 + 보조 6입니다.
- ADR-15는 O 조건 전체나 N값을 확정하지 않았습니다.
- ADR-11~14의 제안이 기존 규칙과 다를 때, 제안 본문의 ‘확정’이라는 표현만으로 Accepted를 덮어쓰지 않습니다.
- ADR-15에는 당시 사용자 확정 지시를 근거로 했으며 작성자의 별도 확인 기록은 없다는 경위가 있습니다. 이를 숨기거나 임의로 승인 상태를 바꾸지 않습니다.

## 상태를 읽는 방법

Accepted ADR 안에서도 예시 매핑·Open Question·기각된 대안을 구분합니다. 예를 들어 ADR-6의 NPC 이름 배정은 잠정이고, R 단계 규칙을 가리키는 ADR 번호는 맞지 않습니다.

새 결정이 나면 해당 조항·변경 이유·영향받는 기획을 연결합니다. 현 상태만 변경하고 진행표·대사·맵을 그대로 두지 않도록 반영 범위를 기록합니다.

[공통 규칙](../01_게임방향/공통규칙.md) · [쟁점 목록](쟁점목록.md) · [결정·미결](README.md)

# InfiniteSplit Workspace

암호화폐 하이브리드 스플릿(그리드) 트레이딩 제품의 umbrella 레포입니다. 배포 산출물은 없고, 자식 서브모듈 포인터와 인수인계 문서만 둡니다.

| 경로 | 레포 | 역할 |
|------|------|------|
| `infinitesplit/` | [postklee15/infinitesplit](https://github.com/postklee15/infinitesplit) | 트레이딩 엔진 + Bot Manager + Socket Relay (한 레포 안 중첩 서비스) |
| `infinitesplit-web-dashboard/` | [postklee15/infinitesplit-web-dashboard](https://github.com/postklee15/infinitesplit-web-dashboard) | 고객 웹 대시보드 (Firebase Hosting) |
| `infinitesplit-admin/` | [postklee15/infinitesplit-admin](https://github.com/postklee15/infinitesplit-admin) | 운영 Admin (Next.js) |
| `infinitesplit-ticker/` | [postklee15/infinitesplit-ticker](https://github.com/postklee15/infinitesplit-ticker) | 공유 시세 서버 (Redis pub) |

다음 에이전트·개발자는 **[docs/handover.md](docs/handover.md)** 부터 읽으세요.

로컬에서 엔진을 켤 때는 반드시 `DRY_RUN=true`. 실서버와 같은 API 키로 켜면 주문이 이중으로 나갑니다.

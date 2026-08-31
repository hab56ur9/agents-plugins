# agents-plugins

개인용 Claude Code 플러그인 마켓플레이스입니다. 플러그인 코드는 각자의 레포에서 관리하고, 이 레포는 `.claude-plugin/marketplace.json` 메타데이터만 관리합니다.

## 사용법

마켓플레이스 추가:

```bash
/plugin marketplace add hab56ur9/agents-plugins
```

플러그인 설치:

```bash
/plugin install <plugin-name>
```

## 플러그인 등록

`.claude-plugin/marketplace.json`의 `plugins` 배열에 entry를 추가합니다.

```json
{
  "name": "my-plugin",
  "source": "https://github.com/hab56ur9/my-plugin",
  "description": "플러그인 설명"
}
```

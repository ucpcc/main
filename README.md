# UCPC 2026 대회 안내 페이지

## Prerequisites

- Ruby 3.3
- Bundler

## Local

Ruby 3.3 환경에서 아래처럼 실행합니다.

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 `http://127.0.0.1:4000` 으로 확인할 수 있습니다.

Apple Silicon Mac에서도 Ruby 3.3 기준으로 그대로 실행하면 됩니다.

플랫폼 관련 오류가 나면 아래를 한 번 실행한 뒤 다시 설치하세요.

```bash
bundle lock --add-platform arm64-darwin
bundle install
```

## Docker Compose

```bash
docker compose up --build
```

브라우저에서 `http://127.0.0.1:4000` 으로 확인할 수 있습니다.

중지할 때는 아래를 실행합니다.

```bash
docker compose down
```

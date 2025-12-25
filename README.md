# 🌤️ Weather

> Real-time weather forecasts

Part of the [zOS Apps](https://github.com/zos-apps) ecosystem.

## Installation

```bash
npm install github:zos-apps/weather
```

## Usage

```tsx
import App from '@zos-apps/weather';

function MyApp() {
  return <App />;
}
```

## Package Spec

App metadata is defined in `package.json` under the `zos` field:

```json
{
  "zos": {
    "id": "ai.hanzo.weather",
    "name": "Weather",
    "icon": "🌤️",
    "category": "utilities",
    "permissions": ["network"],
    "installable": true
  }
}
```

## Version

v4.2.0

## License

MIT © Hanzo AI

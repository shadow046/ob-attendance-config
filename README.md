# OB Attendance Configuration

Public runtime configuration for the OB Attendance mobile app.

Edit `config.json` to change the API server without rebuilding the APK. Increase `config_version` whenever the configuration changes.

- `api_url` must use HTTPS and belong to `ideaserv.online` or one of its subdomains.
- `minimum_app_version` is reserved for enforcing a minimum supported APK version.
- `maintenance` and `message` are reserved for maintenance notices.
- Never store passwords, API keys, tokens, or other secrets here.

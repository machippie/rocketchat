
## Default Variables

### rocketchat_started

Restart app if already running

#### Default value

```yaml
rocketchat_started: true
```

### rocketchat_user

User to run user-specific commands

#### Default value

```yaml
rocketchat_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger

# sample-gihub-action

## Tips
1. 純 linux 的 action 可用下面的 act-cli 指令進行測試

```
act --artifact-server-path ./tmp
```

2. 如果遇上 self-hosted runner 權限不足，請正確配置權限，或到 service.msc 中升權。
https://stackoverflow.com/questions/61048334/how-to-add-privileges-to-the-nt-authority-network-service-account-for-github-act
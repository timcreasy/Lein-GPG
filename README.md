# Lein-GPG

#### Start gpg-agent daemon
```bash
eval $(gpg-agent --daemon)
```

#### Decrypt lein credentials
```bash
gpg --batch --decrypt ~/.lein/credentials.clj.gpg
```

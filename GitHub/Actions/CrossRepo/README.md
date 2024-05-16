# Cross repository sync

GitHub action that will push to another repository.

## Configuration

1. Create SSH key pair locally

```bash
ssh-keygen -t ed25519 -C "Github Automation"
```

2. Add the public key to the target repository as a deploy key
   - This can be added to multiple
3. Add the private key to the source repository as a secret
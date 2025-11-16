# CashOut
Fintech app create using reactjs and outsystems for a DBEA project

## Repository Synchronization

This repository (`rameno0ds/CashOut`) is a fork of the original repository `zeniafoo/Cashout`.

### Important Notes:

**Q: If I push code to this repo, does it update the origin zeniafoo/Cashout?**

**A:** No. Pushing code to `rameno0ds/CashOut` only updates this forked repository. It does NOT automatically update the upstream repository `zeniafoo/Cashout`. To contribute changes back to the upstream repository, you need to create a pull request.

**Q: Can I pull new updates from zeniafoo/Cashout?**

**A:** Yes! This repository has been configured with an `upstream` remote pointing to `zeniafoo/Cashout`. You can pull updates using the commands below.

### How to Pull Updates from Upstream

To sync your fork with the latest changes from the upstream repository:

```bash
# Fetch the latest changes from upstream
git fetch upstream

# Checkout your main branch (or master, depending on your default branch)
git checkout main

# Merge upstream changes into your local branch
git merge upstream/main

# Push the updated branch to your fork
git push origin main
```

### How to Contribute Changes Back to Upstream

To contribute your changes back to `zeniafoo/Cashout`:

1. Push your changes to your fork (`rameno0ds/CashOut`):
   ```bash
   git push origin your-branch-name
   ```

2. Go to the GitHub website and create a Pull Request from your fork to `zeniafoo/Cashout`

3. Wait for the upstream maintainers to review and merge your changes

### Viewing Configured Remotes

To see your configured remotes:

```bash
git remote -v
```

You should see:
- `origin` - Your fork (`rameno0ds/CashOut`)
- `upstream` - The original repository (`zeniafoo/Cashout`)


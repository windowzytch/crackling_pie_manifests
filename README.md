# This repository is a manifest for /e/OS-optimized LOS-based Pie trees for Crackling.

## To get trees using this manifest
In ROM folder before syncing ROM sources...
```
git clone https://www.github.com/windowzytch/crackling_pie_manifests.git .repo/local_manifests -b eos-pie
repo sync --fail-fast --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -jX
```
X=Number of CPU threads

After this, continue as if you synced ROM sources.

## Thanks to
@steadfasterX for helping me make this manifest.
@TeGaX (@Tenshi2112 on Telegram) for providing me the best working sync command.

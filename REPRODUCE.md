# Reproducing this repository

```
python tools/fetch_cap.py <cache> us f f2d f3d f-appx
python tools/build.py cadc <cache>/<reporter>,... <empty folder> --today 2026-11-06
```

Input: static.case.law reporter volume zips (CC0). Gives 25,267 decision commits and one documentation commit.

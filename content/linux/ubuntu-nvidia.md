---
title: "Ubuntu NVIDIA Driver 설치"
date: 2026-07-20
draft: false
---

# Ubuntu NVIDIA Driver 설치

Ubuntu에서 NVIDIA Driver를 설치하는 방법입니다.

## 커널 패키지 설치

```bash
sudo dnf install kernel-devel-$(uname -r) kernel-headers-$(uname -r)
```

## 설치 확인

```bash
nvidia-smi
```
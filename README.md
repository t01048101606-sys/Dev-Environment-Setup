# 개발환경 구축 포트폴리오 (VirtualBox + MobaXterm + VSCode SSH)

## 개요
Oracle VirtualBox에 Ubuntu 리눅스 VM을 생성하고, MobaXterm과 VSCode Remote-SSH를 통해
원격 개발 환경을 구성하는 과정을 단계별로 기록한 레포입니다.

전체 흐름: **Host PC → VirtualBox VM (Ubuntu) → SSH → MobaXterm / VSCode Remote-SSH**

## 목차

| 단계 | 내용 | 링크 |
|---|---|---|
| 1 | VirtualBox 가상머신 생성 (Ubuntu 24.04, 4GB RAM, 2 vCPU) | [01-virtualbox](./01-virtualbox/README.md) |
| 2 | Host-Only 네트워크 구성 (192.168.56.1/24) | [02-network](./02-network/README.md) |
| 3 | VM 내 SSH 서버 활성화 및 확인 | [03-ssh-config](./03-ssh-config/README.md) |
| 4 | MobaXterm으로 SSH 접속 (X11 forwarding 포함) | [04-mobaxterm](./04-mobaxterm/README.md) |
| 5 | VSCode Remote-SSH 연결 | [05-vscode-remote](./05-vscode-remote/README.md) |

## 진행 상태 요약

| 단계 | 상태 |
|---|---|
| VirtualBox VM 생성 | 완료 |
| Host-Only 네트워크 구성 | 완료 |
| VM 내 SSH 서버 활성화 | 완료 |
| MobaXterm SSH 접속 | 완료 |
| VSCode Remote-SSH 연결 | 완료 |

## 다음 단계 (예정)
- (추가 예정 항목을 여기에 기록)

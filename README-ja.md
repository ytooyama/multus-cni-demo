# Kubernetes + Multus CNI on OpenStack Demo

## デモ環境の構成

* OpenStack
* セキュリティグループで必要なポートを開放(6443/tcp 30000-32767/tcp etc ...)
* Kubernetes 1.18 をOpenStackインスタンスで実行
* Multus CNI v3.6を利用
* FlannelもしくはCanalをデフォルトCNIとして利用

## 参考にした情報

* https://github.com/intel/multus-cni
* https://rheb.hatenablog.com/entry/multus_introduction

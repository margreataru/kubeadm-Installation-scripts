## Kubeadm Cluster Setup Scripts

Here is the supporting documentation and video demo.

1. [Documentation - Kubeadm Cluster Setup Guide](https://devopscube.com/setup-kubernetes-cluster-kubeadm/)
2. [Kubeadm workflow explanation and demo video](https://youtu.be/xX52dc3u2HU)

## 🚀 For Kubernetes Certification Aspirants

🚀  CKA, CKAD, CKS, or KCNA exam aspirants can **save $80** today using code **DCUBE20** at https://kube.promo/devops. It is a limited-time offer from Linux Foundation.

For the best savings, opt for the CKA + CKS bundle (**$210 Savings)**. Use code **DCUBE20** at https://kube.promo/bundle

>Note: You have one year of validity to appear for the certification exam after registration

## Kubernetes Learning Roadmap

If you are learning Kubernetes, check out the [kubernetes Learning Roadmap](https://github.com/techiescamp/kubernetes-learning-path)

## If you stop and started the servers. You need to run the below commands. 

1. kubeadm reset
2.  sudo kubeadm init --control-plane-endpoint=13.233.158.166 --apiserver-cert-extra-sans=13.233.158.166 --pod-network-cidr=192.168.0.0/16 --node-name ip-172-31-15-145 --ignore-preflight-errors Swap
3.  mkdir -p $HOME/.kube
4.  sudo cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
5.  sudo chown $(id -u):$(id -g) $HOME/.kube/config
6.  export KUBECONFIG=/etc/kubernetes/admin.conf

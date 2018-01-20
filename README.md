# CNCF Kubernetes Conformance Results
The standard tool for running these tests is
[Sonobuoy](https://github.com/heptio/sonobuoy), and the standard way to run
these in your cluster is with `curl -L https://raw.githubusercontent.com/cncf/k8s-conformance/master/sonobuoy-conformance.yaml | kubectl apply -f -`.

- [kube-ansible](https://github.com/inwinstack/inwinkube-ansible.git)
  - [v1.7](https://github.com/cncf/k8s-conformance/pull/96)
    - [v1.7.11](/kube-ansible/v1.7/v1.7.11)
  - [v1.8](https://github.com/cncf/k8s-conformance/pull/95)
    - [v1.8.2](/kube-ansible/v1.8/v1.8.2)
    - [v1.8.4](/kube-ansible/v1.8/v1.8.4)
    - [v1.8.5](/kube-ansible/v1.8/v1.8.5)
  - [v1.9](https://github.com/cncf/k8s-conformance)
    - [v1.9.0](/kube-ansible/v1.9/v1.9.0)
- [IKM](https://github.com/inwinstack/ikm.git)

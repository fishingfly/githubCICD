# 使用指南
## 前提条件
* 需要k8s1.15以上的集群
* 需要安装tekton/pipeline组件
## kubectl2apply
该文件下是是使用kubectl实现CD过程的。直接运行
```
cd kubectl2apply
kubectl apply -f .
```
流水线就会开始运行。
## client-go2apply
该文件下是是使用client-go实现CD过程的。直接运行
```
cd client-go2apply
kubectl apply -f .
```
流水线就会开始运行。

## 具体实现逻辑请关注微信公众号“云原生手记”，搜索CICD

# go-k8s-sample

## マニフェストファイルのクラスタへの適用
```bash
$ kubectl apply -f myapp.yaml
```

## Deploymentの確認
```bash
$ kubectl get deployments
```

## Podの確認
```bash
$ kubectl get pods
```

## ログの確認
```bash
$ kubectl logs {Pod名}
```

## ポートフォワーディング
```bash
$ kubectl port-forward {Pod名} 8080:80
```
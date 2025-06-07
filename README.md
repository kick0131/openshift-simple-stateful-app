# openshift-simple-stateful-app

```bash
# 名前空間内に定義された"pipeline"サービスアカウントの内容を表示
# イメージのプルに使うシークレットとして自分で作成したdockerhub-secretが表示されていること
oc describe sa pipeline -n simple-stateful-app
```

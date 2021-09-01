# fluentbit
Install Fluenbit di kubernetes menggunakan helm

## Cara install fluentbit menggunakan helm chart

## Menginisialisasi helm

```
$ helm init
```

## Mengupdate repo helm

```
$ helm repo update
```

## Menambahkan repo/chart helm (menyesuaikan dengan kebutuhan)

```
$ helm repo add stable https://charts.helm.sh/stable
```

## Install fluentbit

```
$ helm install stable/fluent-bit -f fluentbit_values.yaml
```

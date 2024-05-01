# CodeNest

CodeNest is an Online Code Editor for Backend/Frontend Apps.

# Prerequisites
- Any Cloud EKS Service
- Any Cloud S3 Bucket Storage

## Installation

### Install Frontend Dependencies

Open Terminals for frontend, init-service and orchestrator-simple service directory

```bash
cd frontend
npm i
```
```bash
cd init-service
npm i
```
```bash
cd orchestrator-simple
npm i
```


Install Ingress Controller for your K8s Cluster

```bash
cd k8s
kubectl apply -f ingress-controller.yaml
```

## Usage

### Start all the above services

```bash
npm run dev
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to add comments as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
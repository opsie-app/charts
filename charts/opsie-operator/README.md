Opsie Operator Server Chart
===========================

Containerize & Orchestrate your Opsie Operator with this simple Helm chart.

## 🤝 Supporting

Development is done by investing time, so any help coming is appreciated. You can sponsor the development  via [Github Sponsors](https://github.com/sponsors/rennokki). 📦

## 🛑 Requirements

- Kubernetes v1.19+

## 🚀 Installation

Install Helm chart repository:

```bash
$ helm repo add opsie https://helm.opsie.app
$ helm repo update
```

Install the Opsie Operator chart:

```bash
$ helm upgrade opsie-operator \
    --install \
    --version=0.1.0 \
    opsie/operator
```

Check `values.yaml` for additional available customizations.

## 🐛 Testing

Coming soon.

## 🤝 Contributing

Please see [CONTRIBUTING](../../CONTRIBUTING.md) for details.

## 🔒  Security

If you discover any security related issues, please email alex@renoki.org instead of using the issue tracker.

## 🎉 Credits

- [Alex Renoki](https://github.com/rennokki)
- [All Contributors](../../../../contributors)

# vaultify
This is a Golang CLI language that will use your opentofu state file or terraform state file encrypt it and send it to your hashicorp vault server, it also can decrypt and pull your state locally.

---

## Install Vaultify

```bash
go install github.com/DFW1N/vaultify@latest
export PATH=$PATH:$(go env GOPATH)/bin
```

---
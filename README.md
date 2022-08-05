# Terraform-azure

### Pré requisito
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

## Instalando ambiente, utilizando tfenv
Repositório de versões do terraform.

### Download do tfenv
https://github.com/tfutils/tfenv
https://registry.terraform.io/providers/hashicorp/aws/latest/docs

### Install Ubuntu
```bash
mkdir .tfenv
git clone https://github.com/tfutils/tfenv.git ~/.tfenv
. ~/.profile
ln -s ~/.tfenv/bin/* ~/.local/bin
sudo vim ~/.profile
/home/rodrigo/.tfenv
```


### Comando básicos para rodar
```bash
terraform -v
terraform init
terraform validate
terraform plan
terraform apply
terraform apply -auto-approve
terraform destroy -auto-approve
terraform fmt -recursive
```

### Install azure-cli
```bash
sudo apt install azure-cli
```

### Login azure
```bash
az login
```


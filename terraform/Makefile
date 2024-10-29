.PHONY: cloudcraft nholuong

cloudcraft:
	terraform init -backend-config=cloudcraft/backend.hcl -reconfigure && terraform apply -var-file=cloudcraft/cloudcraft.tfvars

nholuong:
	terraform init -backend-config=nholuong/backend.hcl -reconfigure && terraform apply -var-file=nholuong/nholuong.tfvars

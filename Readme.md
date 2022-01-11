# Setup

Install tfenv if you haven't already:

```
brew install tfenv
```

Make a note of what terraform version your're currently using:

```
terraform -v #2.2.2
```

```
tfenv install 0.12.31
tfenv use 0.21.31
aws-vault exec vital-dev -- terraform apply
```

To finsh:

```
aws-vault exec vital-dev -- terraform destroy
tfenv use 2.2.2
```

# packer-redhat8-template

This template installs Redhat 8.4 with PCI-DSS hardening.  

Copy variables.json.example to variables.json and build!

* Default user is: redhat/redhat

```bash
packer build -var-file="variables.json" build.json
```

* Tested with packer 1.7.6

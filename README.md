## EL Test Environment



Based on Vagrant CentOS boxes.



Provisioning directory contains a sample playbook to customize the VM.

```bash
├── 6
│   ├── provisioning
│   │   ├── ansible.cfg
│   │   └── playbook.yml
│   ├── tmp
│   └── Vagrantfile
├── 7
│   ├── provisioning
│   │   ├── ansible.cfg
│   │   └── playbook.yml
│   ├── tmp
│   └── Vagrantfile
├── 8
│   ├── provisioning
│   │   ├── ansible.cfg
│   │   └── playbook.yml
│   ├── tmp
│   └── Vagrantfile

```



### Test

```bash
cd version
vagrant up
# Where X = CentOS version
vagrant ssh elX
```


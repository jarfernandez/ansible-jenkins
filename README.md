# ansible-jenkins
Instalación de [Jenkins](https://jenkins.io/) en [CentOS 7 x86_64](https://www.centos.org/) con [Ansible](https://www.ansible.com/). Se incluye la instalación de Maven y de plugins.

La instalación se realiza en una máquina virtual [VirtualBox](https://www.virtualbox.org/) utilizando [Vagrant](https://www.vagrantup.com/). Para crear la máquina virtual y lanzar la instalación de Jenkins, ejecutar el siguiente comando:
```
$ vagrant up
```

Acceder a Jenkins con un navegador a http://localhost:8080

Para obtener la contraseña del usuario `admin` de Jenkins, ejecutar el siguiente comando:
```
$ vagrant ssh -c "sudo cat /var/lib/jenkins/secrets/initialAdminPassword"
```

---

Tags: ansible, centos, configuration management, devops, jenkins, vagrant, virtualbox
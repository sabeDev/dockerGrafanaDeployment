# Grafana on docker
Instructions for this Grafana deployment

# Environments File
You will need to create an environments file: `.env`
This should use the following variables:
```
PASSWORD_LDAP=
VCENTER01=
VCENTER01user=
PASSWORD_VCENTER01=
```

# Authentication 
In the grafana.ini, there is a line `config_file = /etc/grafana/ldap.toml`. This specifies that the configuration file for ldap authetication should be called `ldap.toml` and an example can be found in the config folder, titled `ldap.example`.

Simple rename to `ldap.toml` and add any configuraiton.

# Prometheus
There are configurations for VMWare & BlackBox (website monitoring)
I have left some of my configurations, feel free to remove.




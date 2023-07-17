# Odoo 16

## How to run?

```
docker-compose up -d

docker exec -ti --user root odoo chown -R odoo:odoo /mnt/extra-addons/ var/lib/odoo/

```

## Install odoo

* Go to [http://localhost:8069/](http://localhost:8069/)
* Database Name: odoo

## Custom module

```bash
docker exec -ti odoo odoo scaffold /mnt/extra-addons/custom_module
```

Thank for star to my project!

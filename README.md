# rancher-pipeline-odoo-for-odoo
odoo for odoo

## About branch

* master

for 0doo12.0



## Mount custom addons

* 1: Create a volumes named  "odoo-config"   use directory /odoo-data/odoo-web-data
            a volumes named  "odoo-web"      use directory /odoo-data/odoo-config
            a volumes named   "odoo-addons"  use directory /odoo-data/odoo-addons
* 2: Create three persistentVolumeClaim name  "odoo-config" "odoo-web" "odoo-addons"

   

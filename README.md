# config-plan



## :a: Applications

| :hash: | Projet                                                                             | Description                                          | Application | Type | 
|--------|------------------------------------------------------------------------------------|------------------------------------------------------|-------------|----|
| :one:  | [DNS](https://github.com/uontario/config-dns)                                      | Gestion DNS et Création de zones dans AWS, hébergées par GoDaddy et easyDNS Technologies Inc. | [uof.ca](https://ca.godaddy.com/whois/results.aspx?checkAvail=1&domain=uof.ca) | <img src="https://img.icons8.com/offices/30/000000/dns.png" width=30 height=30 /> |
| :two:  | [moodle](https://github.com/uontario/config-grain-moodle)             | [LMS (Learning Management System)](https://github.com/uontario/LMS) du VRER             | [moodle.uof.ca](https://moodle.uof.ca) | <img src="https://img.icons8.com/clouds/100/000000/server.png" width=30 height=30 /> |
| :three:| [bibliotheque](https://github.com/uontario/src-bibliotheque) | Base de données de la Bibliotheque                   | [bibliotheque.uof.ca](https://bibliotheque.uof.ca) | <img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/000000/external-database-data-analytics-flaticons-lineal-color-flat-icons-4.png" width=30 height=30 /> |
| :four:| [mon](https://github.com/uontario/src-mon)                    | Site d'aide aux étudiants.                           | [mon.uof.ca](https://mon.uof.ca) | <img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/000000/external-database-data-analytics-flaticons-lineal-color-flat-icons-4.png" width=30 height=30 /> |
| :five:| [mahara](https://github.com/uontario/config-grain-mahara)              | Portfolio du VRER                                    | [mahara.uof.ca](https://mahara.uof.ca) | <img src="https://img.icons8.com/clouds/100/000000/server.png" width=30 height=30 /> |
| :six:| [koha](https://github.com/uontario/config-grain-koha)             | [ILS (Integrated Library System)](https://github.com/uontario/ILS) du VRER             | [koha.bibliotheque.uof.ca](https://koha.bibliotheque.uof.ca) | <img src="https://img.icons8.com/clouds/100/000000/server.png" width=30 height=30 /> |
| :seven:| |||
| :eight:| |||
| :nine:| |||
| :one::zero:| [Mon Portail](https://github.com/uontario/config-grain-mon-portail) | Portail des étudiants| :warning: En cours | :question: | 
| :b: | [IDaaS](https://github.com/uontario/IDaaS)      | :id:entity as a Service  | [Azure AD](https://portal.azure.com) | <img src="https://img.icons8.com/external-flat-geotatah/64/000000/external-identity-sensorization-of-things-flat-flat-geotatah.png" width=30 height=30 />  |
| :ab:| [admin ClusterAPI](https://github.com/uontario/config-grappe-admin)      | Site gérant les grappes Kubernetes :wheel_of_dharma:  | [stp.uof.ca](https://stp.uof.ca) | <img src="https://img.icons8.com/external-prettycons-flat-prettycons/47/000000/external-lan-technology-prettycons-flat-prettycons.png" width=30 height=30 /> |
| :cl:| [Coffre](https://github.com/uontario/config-coffre)            | Référentiel gérant les mots de passes et clés :key:  |   |  |




### :gear: Type de Machines
| Type | Description | Commentaires |
|------|-------------|--------------|
|  <img src="https://img.icons8.com/offices/30/000000/dns.png" width=20 height=20 />   | Zone DNS | Zone crée avec [Terraform](https://www.terraform.io) dans AWS | 
| <img src="https://img.icons8.com/clouds/100/000000/server.png" width=20 height=20 /> | VM | VM crée dans AWS sous docker ou docker-compose |
| <img src="https://img.icons8.com/external-flaticons-lineal-color-flat-icons/64/000000/external-database-data-analytics-flaticons-lineal-color-flat-icons-4.png" width=30 height=30 /> | k8s | Grappe Kubernetes :wheel_of_dharma: |
| <img src="https://img.icons8.com/external-prettycons-flat-prettycons/47/000000/external-lan-technology-prettycons-flat-prettycons.png" width=30 height=30/> | ClusterAPI | Gestionnaire de Grappes |

# ansible_cdn_register
Registro de equipos a CDN Red Hat

Requisitos:

  - Conexión SSH con llaves (paso de llaves previo) desde host Ansible a los nodos
  - Registro de hostnames en /etc/hosts o DNS (en caso de usar hostnames en lugar de IPs) en host Ansible
  - Registro de entrada de grupo en /etc/ansible/hosts 
  - Acceso a internet en los nodos a configurar
  - Credenciales para el portal de Red Hat con las suscripciones necesarias
  
Ejecución:

  $ ansible-playbook main.yml

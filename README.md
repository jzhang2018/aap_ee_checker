This ansible playbook is for checking Aansible Automation Platform (AAP) Eecution Environment (EE) dependencies: ansible collections, pythond packages and system tools. 

1. ansible playbook command line:
   ansible-playbook -i localhost, aap_ee_checker.yml -e '{"collection_list": ["community.docker", "dellemc.powermax"], "python_package_list": ["PyU4V", "boto3"], "system_tool_list": ["jq", "unzip"]}'
  
2. It is meant to be used in AAP
   
   

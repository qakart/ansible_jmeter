# ansible_jmeter
The idea is to deploy both jmeter and flask web app in distinct vm using ansible

1.configure the flask ip addr in the roles/runtest/tasks/main.yml ->JHOST=IP@VMflask
2.run  ansible_flask app:this will be done by ansible during deployement phase
3.run jmeter :this will be done by ansible during deployement phase
4. results are in jmeter vm in file results.jtl

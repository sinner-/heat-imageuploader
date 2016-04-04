#heat-imageuploader

`heat stack-create -f imageuploader.yml -P "image_name=testimage;image_url=http://download.cirros-cloud.net/0.3.4/cirros-0.3.4-x86_64-disk.img;os_password=XXX;os_auth_url=https://openstackurl:5000/v2.0;os_username=admin;os_tenant=admin;public_network_uuid111111111-1111-1111-1111-111111111111" imageupload`

`heat stack-delete imageupload`

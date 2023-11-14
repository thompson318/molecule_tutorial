This is me trying to get to grips with using molecule to test ansible roles. I tried this https://www.jeffgeerling.com/blog/2018/testing-your-ansible-roles-molecule first but it seems to be out of date.

molecule init role geerlingguy.example -d docker does not work.

So now tring this
https://ansible.readthedocs.io/projects/molecule/getting-started/

Issues so far:
I've no idea what the note about verify is all about. That seems to be the only mention of verify.yml on that page.

At the moment the bits after adding your own playbook or role don't work. It's a path issue, 
Could not find or access '/home/thompson/software/messing_with_molecule/foo/bar/extensions/molecule/default/foo.bar.my_playbook' on the Ansible Controller.

molecule --version
molecule 6.0.2 using python 3.10 
    ansible:2.16.0
    azure:0.5.0 from molecule_azure
    default:6.0.2 from molecule

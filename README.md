# linux-fundamentals-vagrant

**2. Set Up a Vagrant Server**

<img width="960" alt="vagrant_init" src="https://github.com/user-attachments/assets/0b7fcab4-469f-480e-b7ee-2adad59027fe" />

The above image is initializing vagrantt for deployment.
The vagrant init command creates a Vagrantfile. It defines the settings for the virtual machine, such as:

The box (base image) to use

Networking options

Memory and CPU limits

and automatically import it into the virtualbox.
# login Process
<img width="955" alt="image" src="https://github.com/user-attachments/assets/00eb5a34-223a-4a86-85bd-8b3e15419a1e" />
Vagrant uses SSH to log into the virtual machine.

When you run:
vagrant ssh
You are login automatically without providing username or password.

**3. Explore the Linux File System**

<img width="960" alt="image" src="https://github.com/user-attachments/assets/60aa27bd-bca4-4d94-886f-24a0a617249b" />
This image shows the folder structure.

/home = parent folder for all user home directories

/home/vagrant = the home directory for the vagrant user

/home/vagrant/projects = Project diectory created

/home/vagrant/projects/devOps = is the sub-directory created inside projects directory.

**4. Manage File Permissions and Ownership**

File created with default permission

<img width="959" alt="image" src="https://github.com/user-attachments/assets/f172d284-13f3-42da-af42-05f79b0c1a65" />

File Permission Changed (chown)

<img width="959" alt="image" src="https://github.com/user-attachments/assets/9e9b4ff5-c2ed-4f42-98b6-44f2bff88a33" />








# Output 2.5 Create a Server

---

### How to setup A Windows Server on Virtual Box with Vagrant

#### Step 1

Install virtualbox on your machine, and you can follow this links on how to download and then setup your virturlbox.
[download virtualbox](https://www.virtualbox.org/wiki/Downloads)
[setup virtualbox](https://matthewpalmer.net/blog/2017/12/10/install-virtualbox-mac-high-sierra/index.html)

#### Step 2

download and install vagrant using the following links
[download vagrant](https://www.vagrantup.com/downloads.html)
[install and verify installation](https://www.vagrantup.com/intro/getting-started/install.html)

#### Step 3

Clone this repository

`cd` into the `windows-virtual-env` directory

then run the command `vagrant up`

This command would download the `Microsoft/EdgeOnWindows10` box Virtualbox would need to create the Windows OS.
The box is downloaded from `https://app.vagrantup.com/Microsoft/boxes/EdgeOnWindows1`.

after the download is complete vagrant would then begin provisioning the windows OS on virtualbox.

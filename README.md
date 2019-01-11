# mx-menu-editor_18.11_amd64.deb
MX tool for editing Xfce menu
MX RepositoryMEPIS Community Repository MX and MEPIS Community Repository 
Welcome to the MX Repository and Mepis Community Repository at teharris.net.

MEPIS is a Gnu/Linux distribution based on Debian stable with KDE.  This made it a very solid Operating System and Warren Woodford's skillful implementation made it easy to install and use.

However, working from a stable base sometimes means having older versions of some programs and not having some newer programs at all.  That's where the Mepis Community stepped up.  The Community Packaging Team  backported many newer packages that Mepis users wanted.  This Community Repository was the result of those efforts.

MEPIS is no longer being developed - The MEPIS 12 beta2 iso was the last release - but it is still being used, so these repositories are still being updated.

MX was born from the MEPIS and AntiX communities once it was clear no more MEPIS releases were coming. It is also based on debian stable but uses XFCE instead of KDE. It is a middle weight distribution that runs well on older computers and simply flies on newer ones. It has many custom utilities including tools for easy remastering and tools that make it easy to run MX from a flash drive with persistent home and/or root file systems for those who don't want to install to a hard drive.

The Community supports MX as it did MEPIS for many years, with backports of newer packages and debian builds of wanted packages that are not yet in debian, as well as some custom MX utilities. MX-14 is able to use the packages from the MEPIS 12 Community Repositories as well as its own repositories.

This server hosts the MX Repositories and the MEPIS Community Repositories.

The preferred method of installing packages is by adding these repositories

For MX-17:
deb http://mxrepo.com/mx/repo/ stretch main non-free  (for MX-16 Main repo)

For MX-16:
deb http://mxrepo.com/mx/repo/ mx16 main non-free  (for MX-16 Main repo)

For MX-15:
deb http://mxrepo.com/mx/repo/ mx15 main non-free  (for MX-15 Main repo)

For MX-14:
deb http://mxrepo.com/mepiscr/xfce/ xfce-4.10 main non-free  (for MX-14 Main repo)

For MEPIS 12.0 and MX-14:
deb http://mxrepo.com/mepiscr/repo/ mepis12cr main non-free  (for Mepis 12.0 Main repo)

For MEPIS 11.0:
deb http://mxrepo.com/mepiscr/repo/ mepis11cr main non-free  (for Mepis 11.0 Main repo)

For MEPIS 8.5:
deb http://mxrepo.com/mepiscr/repo/ mepis85cr main non-free  (for Mepis 8.5 Main repo)

For MEPIS 8.0:
deb http://mxrepo.com/mepiscr/repo/ mepis8cr main non-free  (for Mepis 8.0 Main repo)

For MEPIS 7.0:
deb http://mxrepo.com/mepiscr/repo/ mepis7cr main non-free  (for Mepis 7.0 Main repo)

to your /etc/apt/sources.list file and using the normal tools (Synaptic, apt-get or aptitude).

The packages in the Testing repositories haven't been through as much testing as the packages in the main repository. Although the packagers believe them to be safe occasionally issues can arise. If you want to install a package in Testing add this repository

deb http://mxrepo.com/mx/testrepo/ stretch test  (for the MX-17 Testing repo)

deb http://mxrepo.com/mx/testrepo/ mx16 test  (for the MX-16 Testing repo)

deb http://mxrepo.com/mx/testrepo/ mx15 test  (for the MX-15 Testing repo)

deb http://mxrepo.com/mepiscr/mx-test/ mx-14 test  (for the MX-14 Testing repo)

deb http://mxrepo.com/mepiscr/testrepo/ mepis12cr test  (for the Mepis 12.0 Testing repo)

deb http://mxrepo.com/mepiscr/testrepo/ mepis11cr test  (for the Mepis 11.0 Testing repo)

deb http://mxrepo.com/mepiscr/testrepo/ mepis85cr test  (for the Mepis 8.5 Testing repo)

deb http://mxrepo.com/mepiscr/testrepo/ mepis8cr test  (for the Mepis 8.0 Testing repo)

Unlike the repositories for prior versions, the MX-17, MX-16, MX-15, MX-14 and MEPIS 12.0 repositories are signed. If you are running MX Linux the keys are already installed, and can always be re-installed with the included checkaptgpg program. If you are running another distribution, you can download the MX-17 public key, the MX-15/MX-16 public key, the MX-14 public key or the MEPIS 12 public key and add them using 
sudo "apt-key add mx17repo.asc" , sudo "apt-key add mx15repo.asc" , sudo "apt-key add mx14repo.asc" or sudo "apt-key add m12repo.asc" in a Konsole.
You may also download package lists or browse the individual packages hosted on this server here: http://mxrepo.com/mx/repo/pool/main/m/mx-menu-editor/

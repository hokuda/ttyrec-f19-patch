ttyrec-f19-patch
================

A patch to build ttyrec-1.0.8 on Fedora 19. I think it may work on Fedora 20 (not tested).

## How to apply the patch and build

        # yum install glibc-devel
        # yum install libbsd-devel
        # mkdir xxx
        # cd xxx
        # git clone https://github.com/hokuda/ttyrec-f19-patch.git 
        # wget http://0xcc.net/ttyrec/ttyrec-1.0.8.tar.gz
        # tar zxf ttyrec-1.0.8.tar.gz
        # cd ttyrec-1.0.8/
        # patch -p0 < ../ttyrec-f19-patch/ttyrec-f19.patch
        # make

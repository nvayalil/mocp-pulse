## MOC-Pulse

# MOC Player with PulseAudio

Read PREREQUISITES and install the required libraries

# Run MOC by typing mocp on the terminal

Create a file named "config" inside the folder ~/.moc, which is created by MOC on its first run, and add the following inside the "config" file

    SoundDriver = PULSEAUDIO:ALSA:OSS


--------------------------------------------------------------------------------
## How Do I Build and Install It?
--------------------------------------------------------------------------------

Generic installation instruction is included in the INSTALL file.

In short, if you are building from an SVN checkout of MOC (but not if you
are building from a downloaded tarball) then you will first need to run:

	    autoreconf -if

and then proceed as shown below for a tarball.  (If you are using the
tarball but have applied additional patches then you may also need to run
autoreconf.)

To build MOC from a downloaded tarball just type:

        ./configure --with-pulse
        make

And as root:

        make install
    
# See README for further information

## CREDITS
	http://moc.daper.net/
	https://aur.archlinux.org/packages/moc-pulse/ (pathces)


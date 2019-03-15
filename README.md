# smileywarehouse
sudo apt-get install -f --install-recommends linux-generic-lts-xenial xserver-xorg-core-lts-xenial xserver-xorg-lts-xenial xserver-xorg-video-all-lts-xenial xserver-xorg-input-all-lts-xenial libwayland-egl1-mesa-lts-xenial libgl1-mesa-glx-lts-xenial libgl1-mesa-glx-lts-xenial:i386 libglapi-mesa-lts-xenial:i386


On Ubuntu 16.04 LTS, I successfully used the following to disable suspend:

sudo systemctl mask sleep.target suspend.target hibernate.target hybrid-sleep.target
And this to re-enable it:

sudo systemctl unmask sleep.target suspend.target hibernate.target hybrid-sleep.target




https://drive.google.com/open?id=1aF4iabIxUb-ntiAe5oGDwBPl0wnPneoC

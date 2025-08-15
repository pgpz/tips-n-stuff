# this is mainly for people who just switched to Linux from being on Windows all their life and accidentally fucked up by not giving their drive enough space.

> Backup your Windows, Linux & your bootloader EFI partitions before you continue at all. (if you cant, just backup your EFI. your windows & linux are primarily safe while doing this.)

- Boot into your LiveUSB containing any Linux distro (you can also do this via the GParted .iso)

- Download GParted (you most likely already have this but go and try to open to make sure you do.)

- Make sure your Windows & Linux partitions are both unmounted(GParted wont let you proceed if they are mounted, because they are mounted.)

- Proceed with resizing your Windows partition by right-clicking your Windows partition (Resize/Move). It will put you into a prompt where you can resize it. Resize it to whatever size you want.

- Once you are done with that, proceed with going to your EFI bootloader partition under the unallocated space you just created. Right click and go to Resize/Mount.

- Proceed by moving it to the left. Be careful since your system may be different but this is most likely the case for yours. Click apply once done.

- Once you are done with that, proceed by right-clicking and going to Resize/Move on your Linux partition. You can now extend the Linux partition with the new unallocated space you just created. Click apply.

-  Proceed by clicking apply up top on the toolbar in GParted. Wait for it to finish & DO NOT INTERRUPT IT. Reboot once it finishes and enjoy your new space.



<h1>this will work on every single distro of Linux or BSD. have fun partitioning your drives and be safe!!!</h1>



> be thoughtful and assume your drive will not break from this. there is absolutely 0 guarantee on this working, but it will most likely work if you follow these instructions.
> please make a back up of your bootloader if anything.

# i didn't have /var/spool/uucp . instructions say to create it with the following set of commands (this still holds for rxtx 2.1 below, i think):

    * sudo mkdir /var/spool/uucp
    * sudo chmod 775 /var/spool/uucp
    * sudo niutil -destroyval / /groups/uucp users `whoami`
    * sudo niutil -appendprop / /groups/uucp users `whoami`
    * you should install Solaris version of comm.jar file from sun's web site (solaris version http://java.sun.com/products/javacomm/index.html) into /System/Library/Frameworks/JavaVM.framework/Home/lib/ext folder


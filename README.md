# Administration-Directory-Lock

You have two errors here.

1. You are missing a GPG key
2. The dpkg lock file is locked.

You should fix (2) before you fix (1).

Open a terminal and type

CODE:

  sudo lsof /var/lib/dpkg/lock
  
  
  your file was unlock.

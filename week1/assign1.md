### GIT 
distributed version control system designed to handle everything from small to very large projects with speed and efficiency.


## Features

  * Free and Open Source
Git is released under the GNU General Public License version 2.0, which is an open source license. The Git project chose to use GPLv2 to guarantee your freedom to share and change free software---to make sure the software is free for all its users.
   * branching and merging
   The Git feature that really makes it stand apart from nearly every other SCM out there is its branching model.
Git allows and encourages you to have multiple local branches that can be entirely independent of each other. The creation, merging, and deletion of those lines of development takes seconds.

  * Speed
  Git is fast. With Git, nearly all operations are performed locally, giving it a huge speed advantage on centralized systems that constantly have to communicate with a server somewhere.
Git was built to work on the Linux kernel, meaning that it has had to effectively handle large repositories from day one. Git is written in C, reducing the overhead of runtimes associated with higher-level languages. Speed and performance has been a primary design goal of the Git from the start.
  * Secure
  The data model that Git uses ensures the cryptographic integrity of every bit of your project. Every file and commit is checksummed and retrieved by its checksum when checked back out. It's impossible to get anything out of Git other than the exact bits you put in.
  * Reliable and economical
  One of the nicest features of any Distributed SCM, Git included, is that it's distributed. This means that instead of doing a "checkout" of the current tip of the source code, you do a "clone" of the entire repository.

   * Multiple Backups
This means that even if you're using a centralized workflow, every user essentially has a full backup of the main server. Each of these copies could be pushed up to replace the main server in the event of a crash or corruption. In effect, there is no single point of failure with Git unless there is only a single copy of the repository.

   * Any Workflow
Because of Git's distributed nature and superb branching system, an almost endless number of workflows can be implemented with relative ease.

  * Subversion-Style Workflow
A centralized workflow is very common, especially from people transitioning from a centralized system. Git will not allow you to push if someone has pushed since the last time you fetched, so a centralized model where all developers push to the same server works just fine
  
```

 ## Installation
Notes  during installation:
$ sudo apt update
$ sudo apt upgrade
$ sudo add-apt-repository ppa:git-core/ppa
$  sudo apt install git





```



## References

 [Git](https://git-scm.com/)
 
 [dsea](https://github.com/espirado/dsea/documents/Git and Github.pdf)


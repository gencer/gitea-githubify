# gitea-gihubify
GitHub Theme for Gitea (and for Gogs)

This repo contains patch files for Gitea to make Gitea looks like GitHub.

**Note** **that**, patch size is huge, because it still needs many fixes. Until it fixed and proper version released, I will decrease patch size.

Install
==

Upload **patch.css** and **patch-ext.css** files to **public** dir.

Open **gogs.css** for Gogs or **index.css** for Gitea. Put this two lines at to **top**:

    @import url("patch.css");
    @import url("patch-ext.css");
    
Save and close. Thats all. Do not forget to clear browser cache. (__or CTRL+F5__)

Extra patch:
===
Extra patch files is required for customized view. If you only upload patch.css file, it won't look better. 

Screenshots:

![1](/ss/1.png?raw=true "")
![2](/ss/2.png?raw=true "")
![3](/ss/3.png?raw=true "")
![4](/ss/4.png?raw=true "")
![5](/ss/5.png?raw=true "")
![6](/ss/6.png?raw=true "")
![7](/ss/7.png?raw=true "")

Improved repo name (NEW)
---
![9](/ss/9.png?raw=true "")

Improved repository header (NEW)
---
![13](/ss/13.png?raw=true "")


Licensed under **MIT** License

# Usage

Copy vars.example.yml to vars.yml

Edit vars.yml appropriately.

Create a build host which *must* be a 32-bit machine running Ubuntu 14.04.

Add this build host to your ansible hosts file as
```
[steam_ponscripter_build]
your_host_here
```

run `ansible-playbook steam-build.yml`

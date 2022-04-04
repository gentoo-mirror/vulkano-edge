# Vulkano-edge

A Gentoo Vulkan Repository using the GPL-3.0 License.

# Information

- Vulkan v1.3.210 has new extentions. To run those extentions check to see if your driver supports it.

# Repository Info

- Anything Vulkan related besides Vulkan-headers and Vulkan-loader will not be found here unless it's pushed.
- This repo will be always try to be updated to the latest, trying to have all versions for compatibility.

# How to install

Add this into /etc/portage/repos.conf/vulkano-edge.conf:

```
[vulkano-edge]
location = /usr/local/portage/
sync-type = git
sync-uri =
masters = gentoo
auto-sync = yes
```
Afterwards run

```emaint sync -r steam-overlay```

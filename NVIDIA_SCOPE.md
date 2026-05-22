# NVIDIA scope notes

Included NVIDIA endpoints are limited to AI/API use cases:
- api.nvcf.nvidia.com
- integrate.api.nvidia.com
- build.nvidia.com
- ngc.nvidia.com

Not included:
- nvidia.com (root)
- developer.nvidia.com
- www.nvidia.com
- download.nvidia.com
- gfwsl.geforce.com
- ota.nvidia.com
- any GeForce/driver/CDN/update domains

Reason: avoid sending GPU driver downloads and general NVIDIA traffic through the AI proxy group.

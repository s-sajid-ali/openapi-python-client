---
default: major
---

# Default to using httpx2 instead of httpx causing the following breaking API changes:
- `set_httpx_client` -> `set_httpx2_client`
- `get_httpx_client` -> `get_httpx2_client`
- `set_async_httpx_client` -> `set_async_httpx2_client`
- `get_async_httpx_client` -> `get_async_httpx2_client`

# Astro file handle leak minimal example

This shows how when building a huge number of pages (in the order of thousands) the build process allocates/leaks excess file handles leading into an exception `fs`.

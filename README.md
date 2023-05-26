# raytracers
I like to make raytracers and I want a repo which can test them as I implement them.

Each implementation can be tested against outputs from the [official pbrt implementation](https://github.com/mmp/pbrt-v4/tree/master). So each of my implementations needs to be able to parse the [pbrt-v4 file format](https://pbrt.org/fileformat-v4).

# Testing
Input data for tests is kept in [/assets/test-data/](/assets/test-data/) and is run in order. Beginning with a very basic implementation of diffuse lighting and rendering a sphere and each subsequent test adds more features. Each test is compared against the corresponding image in [/assets/expected/](/assets/expected/).

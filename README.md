Collection of example CI files to compile CMake programs on all plateforms

basic.yml : native approach, one job per OS. Different artifacts for every binary
matrix.yml : matrix approach. Different artifacts for every binary
matrix_bundled.yml : matrix approach, one artefact contains every binary, one folder per OS

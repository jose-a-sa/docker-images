FROM --platform=arm64 ubuntu:22.04

# APT Update
RUN apt-get update && apt-get upgrade -y

# APT install (base) packages
RUN apt-get install -y build-essential cmake linux-tools-common git \
    pkg-config valgrind ninja-build doxygen gcc-12 clang clang-format clang-tidy gdb

RUN apt-get install -y libgtest-dev

RUN apt-get install -y libboost-all-dev

# plt
plt (Propositional Logic Transformation) - apply CNF transformation in propositional formula.
 
# Requirements
- [cmake](https://cmake.org/)
- [ninja-build](https://ninja-build.org/)
- A compiler with support c++ 17
- if you build `pll` test coverage, you need to be installed [gtest](https://github.com/google/googletest)

# How to clone and compile
- Clone this repo as: ```git clone --recurse-submodules "https://github.com/fgarcia0x0/plt.git"```
- In terminal, type: ```cd plt && cmake -S . -B build -GNinja -DCMAKE_BUILD_TYPE=Release```

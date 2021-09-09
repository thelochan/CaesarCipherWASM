# WASMCPP
A WASM C++ test

Emscripten syntax: emcc -Os -s STANDALONE_WASM -s EXPORTED_FUNCTIONS="['_caesarEncrypt', '_caesarDecrypt']" -Wl,--no-entry "caesar.cpp" -o "caesar.wasm"


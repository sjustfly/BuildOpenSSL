# BuildOpenSSL
build openssl to .a

use this shell build `https://github.com/adib/openssl-xcframeworks/tree/develop/BigSur`

support architectures

`ios-sim-cross-x86_64 ios-sim-cross-arm64 ios-cross-armv7 ios64-cross-arm64 mac-catalyst-x86_64 mac-catalyst-arm64 tvos-sim-cross-x86_64 tvos64-cross-arm64 macos64-x86_64 macos64-arm64 watchos-cross-armv7k watchos-cross-arm64_32 watchos-sim-cross-i386`

If you want to merge the architectures together    
use command
`lipo -create /Users/xx/Downloads/a/libssl.a /Users/xx/Downloads/b/libssl.a -output /Users/xx/Downloads/c/libssl.a`

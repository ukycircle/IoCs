# Sample Hashes

notation: sha256 (filename, family)

## Windows
- e6432f09b652cd3f577cde0671ef18ad9cd6fe5d0b45460a740254dd097f4d51  (win.exe, Chaos)
- fb69b4b5637a6b7aa40ba7ae56ed617d375f67984c3028a7607e1764fdda8490  (as55.exe, Chaos)
- 45680b3402dc7ae2f51f75bafbfddb8a29398818a48a6857342ea6385ad66b11  (as55_unpacked.exe, Chaos)
- 68d90782ad76c3f9f3163e99c57697cfb1754035d5da84474f44f8c3636257e2  (bots.exe, BillGates)
- 6aec0f5b6eaeb528ba6f17600193dd5bd0f621ba3c27284bf29bce56728e9ec7  (win.exe, Chaos)

## Linux
- 866c3d8c7ca053516f45108832840680bc0649a669f4b94fd369c471213686d6  (linux_386, Chaos)
- 5eceb1ab11ba3aebbd27b2e9cd6b678384abb6acc7379e284e518f09b6ffb8e1  (linux_amd64, Chaos)
- 0defd338d2eccc8b865398e038696a1138743631a25b3627b48db3ea40d99460  (linux_arm5, Chaos)
- b352fb43754188683f7954610e4d9840ea937d667294f707e97f42d66745be5a  (linux_arm6, Chaos)
- 4b326a38b4894fa291cb36d9206c3de2ebb34142aec752114e992bb3168257e0  (linux_arm64, Chaos)
- 921864140e56e6e78403dc6fd64f0dee81accea429935607f8723068816a6bf5  (linux_arm7, Chaos)
- 7da8f553216859d9f582f69f5183373a61bf02dad9dd3fe466312bcce1a207d6  (linux_mips, Chaos)
- 36d56fedde4a58c426318b6db2c7f8ee68df6f75f9c1ce90ce8324e32c07e9e9  (linux_mips64, Chaos)
- 36d56fedde4a58c426318b6db2c7f8ee68df6f75f9c1ce90ce8324e32c07e9e9  (linux_mips64_softfloat, Chaos)
- 8203cedb62d6b6ec1b30eacb4deb351605e1cf4406bacb0ddd99452c8e7aa10c  (linux_mips64el, Chaos)
- 8203cedb62d6b6ec1b30eacb4deb351605e1cf4406bacb0ddd99452c8e7aa10c  (linux_mips64el_softfloat, Chaos)
- 0a2d69b2fbcb32b4468cca886d0eade13da476b0d47808e470287ea5ac8827e7  (linux_mips_softfloat, Chaos)
- 669760d3708d4040d7c10824adbe25f0b96d42a570455325ddf310a4af863898  (linux_mipsel, Chaos)
- 586e4850c20056394a8cd538754c33ee5d095e35788a7862fb8908e4cdc7af3c  (linux_mipsel_softfloat, Chaos)
- 2d77592c3c46ba05a18655430e5a191a16e68c308ed1406a73a4dae156adca32  (linux_ppc64, Chaos)
- 9397b2dc1b47fbc3c49feec22d1b882fcbe5387ca5827341757847e49551327d  (linux_ppc64el, Chaos)
- 9d05b6afbae1ec31ff2d82f1ff9062f7cbfab6346329261a4f19bad4f74d7ee8  (bots, BillGates)
- 3a987e4972535a9e992253dce168e0499d8b6dfc6e4e19cc8be6153397668967  (syn, BillGates)
- ec0c849db557051d2f6cdef6973ccc04b246fc58dca933cbb9fa1a7c7c01e71f  (386.sh, Chaos)

## Downloads

- 103.254.72[.]193:808
- 67.198.237[.]116
- zf.gouzapay[.]cn/muma


# C2s
- ares.goodl1[.]com:10099
- ars1.wemix[.]cc:9090
- tf.xn--9kqv03dn4b[.]xyz:8080


# C2 files

http://C2:808/ + 'filename'

c9413c5291b8cdaf588a44311ac45c724f51d137328ce57b26d0eec388e562ea  cve.txt
f2f9ca9ff0cb7eed58c756649005c78fe847c56c2ba415d15dd8abbd07a3e10f  download.sh
6d6ee4c09e7b2688a9b9850b921b78cf72f2c7352662a9ff4067ca016b1162ed  password.txt

# C2 panels

- ares.goodl1[.]com:8080
- ars1.wemix[.]cc


# Behaviors of Chaos malware

We have observed this behaviors:

1. Persistence

Some chaos malware use crond.service.

2. DNS query

- www.google.com
- C2 Server

3. C2 access

Some chaos malware use to connect to C2 server <b>using TLSv1.3</b>.

4. Get password.txt

- User-Agent: <b>Go-http-client</b>

5. ARP Broadcast

6. Lateral-movement using ssh

- username: <b>root</b>
- client: <b>SSH-2.0-Go</b>


# References
- https://blog.lumen.com/chaos-is-a-go-based-swiss-army-knife-of-malware/
- https://github.com/blacklotuslabs/IOCs/blob/main/Chaos_IoCs.txt
- https://hackmd.io/F-SJlk7qRg-8xYZJjzM6lw
- https://hackmd.io/XUdwubU3R-SvwVH8yBoKrg

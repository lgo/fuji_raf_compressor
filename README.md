# fuji_raf_compressor
Process uncompressed RAF into compressed RAF, a lossless compressed format.

Several older Fuji cameras do not support producing lossless compressed RAF files, so converting uncompressed to compressed RAF files is an instant win for saving drive space while preserving original formats. As far as I could find, there are no available tools to compress RAF files.

Cameras which can only produce uncompressed RAF includes:
- XT-10 (my camera!)

**Note: this is not done yet!**

## TODO
- [ ] Read through RAF decoding algorithm in darktable rawspeed ([decompressor](https://github.com/darktable-org/rawspeed/blob/develop/src/librawspeed/decompressors/FujiDecompressor.h) and [uncompressed reader](https://github.com/darktable-org/rawspeed/blob/3f9b3032caf7836faf08af38cb3d6799f1155555/src/librawspeed/decoders/RafDecoder.cpp#L113-L172))
- [ ] Read through RAF decoding algorithm in LibRaw ([decompressor](https://github.com/LibRaw/LibRaw/blob/1dbed6b7e65ef2ebd0c3f82722a0b7f3990845f7/src/decoders/fuji_compressed.cpp) and [uncompressed reader](https://github.com/LibRaw/LibRaw/blob/1dbed6b7e65ef2ebd0c3f82722a0b7f3990845f7/src/utils/open.cpp#L653-L710))

# iso-build
Updated Manjaro Cinnamon CE (Daily Rebuilds)
<br> Based on this <a href="https://github.com/pheiduck/iso-profiles">iso-profiles<a/>

## How to use the ISO file:

1. The z01 and zip file must be combined. <br>
`cat manjaro-cinnamon-21.0.7-210706-linux510.iso.z01 manjaro-cinnamon-21.0.7-210706-linux510.iso.zip > manjaro-cinnamon-21.0.7-210706-linux510.zip`

2. Unzip the combined zip file. <br>
`unzip manjaro-cinnamon-21.0.7-210706-linux510.zip`
```
Archive: manjaro-cinnamon-21.0.7-210706-linux510.zip
warning [manjaro-cinnamon-21.0.7-210706-linux510.zip]:  zipfile claims to be last disk of a multi-part archive;
  attempting to process anyway, assuming all parts have been concatenated
  together in order.  Expect "errors" and warnings...true multi-part support
  doesn't exist yet (coming soon).
warning [manjaro-cinnamon-21.0.7-210706-linux510.zip]:  2044723200 extra bytes at beginning or within zipfile
  (attempting to process anyway)
file #1:  bad zipfile offset (local header sig):  2044723204
  (attempting to re-compensate)
  inflating: manjaro-cinnamon-21.0.7-210706-linux510.iso  
```
3. 🎉 Finally, you can flash the ISO file to a USB drive or use it in a virtual machine.

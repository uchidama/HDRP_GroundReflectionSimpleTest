# HDRP_GroundReflectionSimpleTest
<a href="https://gyazo.com/3041724f3ffbfc5d6424015b8cf4bfc0"><img src="https://i.gyazo.com/3041724f3ffbfc5d6424015b8cf4bfc0.png" alt="Image from Gyazo" width="640"/></a>  
HDRP Ground Reflection Simple Test.  

# 作り方
- High Definition RPでプロジェクト作成
- GameObject -> 3D Object -> Mirror でミラー置く
- Mirrorをdisableにする  
- Example Assets -> Workshop Set -> Ground
    - Mesh Render -> Elements 0を、Mirrorのマテリアル"DefaultHDMirrorMaterial"にする  
  
<a href="https://gyazo.com/5e3d44ce2a31ef1c66ae918c7fad9fcc"><img src="https://i.gyazo.com/5e3d44ce2a31ef1c66ae918c7fad9fcc.jpg" alt="Image from Gyazo" width="640"/></a>

- Mirrorに設定されている"Planar Reflection Probe"をCopy Component  
  
<a href="https://gyazo.com/1e8994c497b7c02827bd8b51c5140d74"><img src="https://i.gyazo.com/1e8994c497b7c02827bd8b51c5140d74.png" alt="Image from Gyazo" width="640"/></a>

- Groundに"Paste Component as new"で"Planar Reflection Probe"をGroundに追加  
  
<a href="https://gyazo.com/04e1c4d9c74aa9e0ee955125c61be7f1"><img src="https://i.gyazo.com/04e1c4d9c74aa9e0ee955125c61be7f1.png" alt="Image from Gyazo" width="640"/></a>

# 必要要件
- Unity 2019.4.0f1 or later

# License
[Unlicense](https://unlicense.org/)

# dragonbones-site

Bản site DragonBones (static) kèm DragonBones Viewer đã chỉnh sửa, chạy trên GitHub Pages.

- Site: https://hieunvthe1studio.github.io/dragonbones-site/
- Viewer (kéo thả `*_ske.dbbin|json`, `*_tex.json`, `*_tex.png`): https://hieunvthe1studio.github.io/dragonbones-site/viewer/v1/index.html

Thay đổi so với bản gốc, trong `viewer/v1/`:
- Thêm nút **Loop** bật/tắt lặp animation (áp dụng cả armature con).
- Atlas được gắn theo tên skeleton, không phụ thuộc trường `name` trong `*_tex.json`; sửa lỗi atlas nhiều trang dùng sai ảnh.

Lưu ý: một số link menu trong `cn/` và `en/` dùng đường dẫn tuyệt đối (`/en/learn.html`) nên bị 404 khi site nằm dưới `/dragonbones-site/`.

---

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>
<br />
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
<br />
本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议</a>进行许可。

Copyright (c) 2012-2018 The DragonBones team and other contributors.

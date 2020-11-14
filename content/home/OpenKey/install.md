+++
weight = 50
+++

## Cài đặt

---

**Cài đặt thủ công**

Tải bản mới nhất từ [OpenKey](https://github.com/tuyenvm/OpenKey/releases/latest),<br> 
mở file `dmg` ra rồi kéo thả `OpenKey.app`<br>
vào thư mục `Application`.

---

**Cài bằng Homebrew**

Nếu chưa cài Homebrew, mở terminal, nhập

```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

---

- Gõ lệnh sau để homebrew tự cài OpenKey cho bạn

```
$ brew cask install openkey
```

- Kiểm tra phiên bản OpenKey

```
$ brew cask info openkey
```

- Để update phiên bản mới nhất của OpenKey

```
$ brew cask upgrade openkey
```
---

### Note
<br>

OpenKey cần cấp quyền quản trị, các bạn vào<br>
*System Preferences -> Security & Privacy -> Accessibility*,<br>
kích hoạt `OpenKey.app`.

<br>

**Lưu ý: Không tắt quyền khi đang dùng OpenKey**.

---

![Guide](https://github.com/doanhmaple/hdh-slide/raw/main/images/openkey-guide.png "Accessibility").
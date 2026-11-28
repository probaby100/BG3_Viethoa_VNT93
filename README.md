# Hướng Dẫn Cài Đặt & Sử Dụng Bộ Việt Hóa Baldur's Gate 3

Chào mừng bạn đến với bộ Việt hóa **Baldur's Gate 3** (hỗ trợ đầy đủ phông chữ tiếng Việt giao diện, lựa chọn thuật ngữ linh hoạt và gói lồng tiếng Người Dẫn Truyện toàn diện).

---

## 1. Cấu trúc 4 thư mục trong bộ cài

Bộ Việt hóa được chia sẵn thành **4 thư mục độc lập** để bạn tự do lựa chọn phong cách trải nghiệm phù hợp nhất:

1. **`Dịch 50` *(Việt hóa giữ thuật ngữ gốc Tiếng Anh)***
   - Toàn bộ cốt truyện, lời dẫn truyện, hội thoại nhân vật, sách vở, thư từ và phần mô tả tác dụng được dịch sang tiếng Việt mạch lạc, tự nhiên.
   - **Giữ nguyên Tiếng Anh** cho: Tên kỹ năng/phép thuật, Trang bị/vật phẩm, Nội tại/Chuyên môn (Feats), Trạng thái (Statuses), Lớp nhân vật (Classes/Subclasses), Chủng loài (Races), Chỉ số & cơ chế D&D (Saving Throw, Attack Roll, Advantage...), Địa danh, Thế lực và Tên nhiệm vụ.
   - **Phù hợp với:** Người chơi muốn hiểu trọn vẹn cốt truyện tiếng Việt nhưng vẫn dễ dàng tra cứu Wiki tiếng Anh, xem hướng dẫn Build nhân vật quốc tế hoặc quen thuộc với hệ thống D&D 5e.

2. **`Dịch 100` *(Việt hóa toàn diện 100% - Không kèm âm thanh lồng tiếng)***
   - Việt hóa trọn vẹn 100% toàn bộ văn bản trong game (bao gồm cả tên trang bị, phép thuật, địa danh, nhiệm vụ, chủng loài, thế lực...).
   - **Phù hợp với:** Người chơi muốn đắm chìm hoàn toàn vào thế giới giả tưởng thuần Việt, hoặc dùng kết hợp với gói **`Lồng tiếng`** để khớp 100% từng chữ giữa phụ đề và giọng đọc.

3. **`Lồng tiếng` *(Tùy chọn - Lồng tiếng Việt Người Dẫn Truyện / Narrator)***
   - Chứa trọn bộ `7.630` tệp âm thanh `.wem` lồng tiếng Việt cho Người Dẫn Truyện (Narrator) xuyên suốt toàn bộ game cùng hệ thống tệp `Timeline` đồng bộ thời lượng cắt cảnh.
   - Chỉ khi bạn chép đè thư mục này vào game thì game mới phát giọng lồng tiếng Việt của Người Dẫn Truyện; giọng nói của các nhân vật đồng hành và NPC khác vẫn giữ nguyên bản diễn xuất tiếng Anh gốc.

4. **`Hướng dẫn` *(Tài liệu tra cứu & Quy tắc dịch thuật)***
   - `HUONG_DAN_CAI_DAT_NGUOI_CHOI.md`: Tài liệu hướng dẫn cài đặt, chuyển đổi và gỡ cài đặt (tệp bạn đang đọc).
   - `BG3_Tra_Cuu_Thuat_Ngu_Viet_Anh.xlsx`: Bảng Excel tra cứu nhanh hàng nghìn thuật ngữ **Việt ⇄ Anh** chia theo từng nhóm (Vật phẩm, Phép thuật, Nội tại, Trạng thái, Địa danh, Nhiệm vụ, Nhân vật...) dành cho người chơi dùng bản `Dịch 100` khi cần đối chiếu với Wiki tiếng Anh.
   - `BG3_Glossary_ThuVienChuan.json`: Thư viện thuật ngữ chuẩn định dạng JSON dùng để đồng bộ dịch thuật.
   - `GEMINI.md` & `quy_tac_dich_bg3_google_antigravity.md`: Tài liệu quy chuẩn dịch thuật dành cho AI và cộng tác viên biên tập.

---

## 2. Hướng dẫn cài đặt

### Bước 1: Xác định thư mục gốc cài đặt game `Baldur's Gate 3`
Mở thư mục cài đặt gốc của game trên máy tính của bạn (nơi chứa sẵn hai thư mục `bin` và `Data`).
- **Ví dụ trên Steam:** `...\Steam\steamapps\common\Baldurs Gate 3\`
- **Ví dụ trên GOG / Bản rời:** `...\Baldur's Gate 3\`

### Bước 2: Cài đặt phần Phụ đề & Giao diện Tiếng Việt *(Chọn 1 trong 2 bản)*
- **Nếu muốn chơi bản giữ thuật ngữ Tiếng Anh:** Mở thư mục **`Dịch 50`**, sao chép (**Copy**) thư mục **`Data`** bên trong và dán (**Paste / Ghi đè**) thẳng vào thư mục gốc của game `Baldur's Gate 3`.
- **Nếu muốn chơi bản Việt hóa toàn diện 100%:** Mở thư mục **`Dịch 100`**, sao chép (**Copy**) thư mục **`Data`** bên trong và dán (**Paste / Ghi đè**) thẳng vào thư mục gốc của game `Baldur's Gate 3`.

> **Lưu ý:** Không cài cả hai bản cùng lúc — bản nào bạn chép vào sau sẽ ghi đè lên bản trước. Khi vào game, ngôn ngữ Tiếng Việt và bộ phông chữ tiếng Việt sẽ tự động được kích hoạt ngay mà không cần chỉnh sửa gì thêm.

### Bước 3: Cài đặt thêm gói `Lồng tiếng` *(Không bắt buộc)*
Nếu bạn muốn bật giọng đọc tiếng Việt cho Người Dẫn Truyện:
1. Sau khi hoàn tất Bước 2, mở thư mục **`Lồng tiếng`**.
2. Sao chép (**Copy**) thư mục **`Data`** bên trong và dán (**Paste / Ghi đè**) tiếp vào thư mục gốc của game `Baldur's Gate 3`.

> **Mẹo nhỏ:** Giọng đọc trong gói **`Lồng tiếng`** được thu âm theo văn bản thuần Việt của bản **`Dịch 100`**. Bạn vẫn có thể cài chung **`Dịch 50` + `Lồng tiếng`** hoàn toàn bình thường (phụ đề sẽ hiển thị thuật ngữ Tiếng Anh trong khi giọng đọc phát thuật ngữ Tiếng Việt tương ứng), hoặc dùng **`Dịch 100` + `Lồng tiếng`** để chữ và tiếng trùng khớp tuyệt đối.

---

## 3. Cách chuyển đổi hoặc gỡ cài đặt sạch sẽ

Các tệp gốc của game Baldur's Gate 3 đều nằm an toàn bên trong các gói nén `.pak`, nên việc cài đặt hoặc gỡ bỏ bộ Việt hóa **không bao giờ làm hỏng tệp gốc của game**.

### Chuyển đổi qua lại giữa `Dịch 50` và `Dịch 100`
- Chỉ cần mở thư mục của bản bạn muốn đổi sang (`Dịch 50` hoặc `Dịch 100`), **Copy** thư mục **`Data`** bên trong và **Paste (Ghi đè / Replace all)** vào thư mục gốc của game.

### Gỡ riêng phần `Lồng tiếng` (Trở về giọng Narrator Tiếng Anh gốc, giữ nguyên chữ Tiếng Việt)
Vào thư mục gốc của game `Baldur's Gate 3` và xóa 3 thư mục con sau:
- `Data\Mods\Gustav\Localization\English\Soundbanks`
- `Data\Public\Gustav\Timeline`
- `Data\Public\GustavDev\Timeline`

### Gỡ hoàn toàn bản Việt hóa (Trở về 100% Tiếng Anh nguyên bản)
Ngoài 3 thư mục lồng tiếng ở trên (nếu đã cài), bạn xóa thêm 2 thư mục sau trong thư mục gốc của game:
- `Data\Localization`
- `Data\Public\Game\GUI`

Chúc bạn có những giờ phút phiêu lưu đáng nhớ tại vùng Bờ Kiếm và thành Baldur's Gate!

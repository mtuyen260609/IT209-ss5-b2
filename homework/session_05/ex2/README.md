# Báo cáo Bài 2: Tái cấu trúc lịch sử commit bằng Interactive Rebase

## Cấu hình trình soạn thảo Interactive Rebase (Mô phỏng)
```text
pick e3a5b2c feat: khoi tao module auth
squash b2a4c1d fix typo
squash c3d5e2f adds utility functions
drop d4e6f3a add temp file for debug
```
*Ghi chú: Đã thay đổi 'pick' thành 'squash' (hoặc 's') cho 2 commit giữa để gộp, và 'drop' (hoặc 'd') cho commit cuối chứa file rác.*
*Sau đó đã lưu thông điệp commit mới là: `feat: hoan thien module authentication`.*

## Lịch sử commit sau khi hoàn tất
```
2bdfa56 feat: hoan thien module authentication
3019d8e Initial commit
```

# EV Reservation — Mobile App

App React Native duy nhất cho cả 2 role `customer` và `station_owner`, điều hướng khác nhau theo role sau khi đăng nhập (không tách 2 app riêng). Xem chi tiết kiến trúc, wireframe, user flow trong tài liệu gốc của dự án: [UI_UX_Wireframes.md](../UI_UX_Wireframes.md), [CLAUDE.md](../CLAUDE.md).

## Tech stack

- React Native (Expo/CLI)
- Backend API: xem [backend/CLAUDE.md](../backend/CLAUDE.md)

## Cấu trúc dự kiến

```
mobile-app/
└── src/
    ├── features/user/     # màn hình, logic riêng cho customer
    ├── features/station/  # màn hình, logic riêng cho station_owner
    └── shared/             # component, hook, util dùng chung 2 role
```

## Trạng thái hiện tại

Chưa khởi tạo project (chưa chạy `create-expo-app`/RN CLI) — repo mới có mỗi file này để bắt đầu track Git.

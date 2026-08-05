# TTTN 2026 - Nhóm 7

Đồ án tốt nghiệp: web bán hàng (client + trang quản trị).

## Stack

NestJS 11 + TypeORM + PostgreSQL 16, Redis, BullMQ, Elasticsearch, VNPay/MoMo, chatbot Claude API.
Chi tiết kiến trúc: [.skill/backend/architecture.md](.skill/backend/architecture.md).

## Quy ước nhánh

- `dev` — nhánh tổng, tích hợp code của cả nhóm.
- `oanh`, `vy`, `vi`, `nhan` — nhánh làm việc cá nhân của từng thành viên, tạo từ `dev`.

Mỗi thành viên phát triển trên nhánh của mình, mở PR để merge vào `dev` khi xong.

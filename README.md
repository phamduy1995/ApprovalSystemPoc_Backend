# Hệ thống phê duyệt (Approval System PoC)

Đây là phần backend của dự án Proof of Concept cho hệ thống phê duyệt, được xây dựng bằng ASP.NET Core 9.

## Yêu cầu hệ thống

- .NET 9 SDK
- Visual Studio 2022 hoặc Visual Studio Code

## Cài đặt

1. Clone repository:
```bash
git clone <repository-url>
cd ApprovalSystemPoC/backend
```

2. Khôi phục các packages:
```bash
dotnet restore
```

3. Chạy ứng dụng:
```bash
dotnet run
```

Ứng dụng sẽ chạy mặc định tại https://localhost:7125 và http://localhost:5125

## API Endpoints

### GET /weatherforecast
Trả về dữ liệu dự báo thời tiết mẫu (API demo).

## Công nghệ sử dụng

- ASP.NET Core 9
- OpenAPI/Swagger

## Cấu trúc dự án

Dự án hiện tại là một API đơn giản với cấu trúc cơ bản của ASP.NET Core. Khi phát triển thêm, cấu trúc sẽ được mở rộng theo mô hình nhiều lớp (multi-tier architecture). 
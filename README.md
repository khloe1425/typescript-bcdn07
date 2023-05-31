# Khởi tạo file package.json.
> npm init -y
# Cài typescript cho toàn bộ dự án.
> npm i typescript -g
# Khởi tạo file config typescript.
> tsc --init || npx tsc --init

### Chú Thích.
- "target": "ES2016", => version của js mà ts muốn chuyển về. Không để es5 để hỗ trợ nhiều thư viện, typescript không mạnh về việc chuyển đổi cú pháp, "babel, swc(mới)"
- "module": "commonjs", => chuyển về dạng require, export.modules.
- "outDir": "./js",   => khi build file ts sẽ ra tạo ra js ở trong thư mục js

> đối với start: npm start
> đối với tên khác: npm run [ten]
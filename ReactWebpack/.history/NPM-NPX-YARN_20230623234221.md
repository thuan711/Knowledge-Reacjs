- NPM
    - Project scope (cài thư viện vào dự án)
        - npm install react react-dom => dependencies
        - npm i react react-dom => dependencies

        - npm install --save-dev react react-dom => devDependencies
        - npm i -D react react-dom => devDependencies

        - npm uninstall react react-dom
    
    - Global scope (cài thư viện vào sever)
        - npm i --global create-react-app
        - npm i -g create-react-app

        - npm uninstall -g create-react-app

- NPX: Node: => NPM, NPX
    - Tại sao dùng NPX?
    - Gặp lỗi khi: npx create-react-app tiktok (cài global)

- YARN & NPM (đều là quản lí thư mục) 
    - npm cài tuần tự từng thự mục
    - yarn cài nhiều thư viện 1 lúc. tải về lưu ở đâu đó trên máy khi cần lấy ra không cần down lại.
YARN install

- Lưu ý
    - Luôn bật development server (npm start || yarn start)
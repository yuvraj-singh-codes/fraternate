

The MERN Marketplace application will allow users to become sellers, who can manage  shops, and add the products they want to sell in each shop. Admin can control functionality of Seller Users who visit MERN Marketplace will be able to search for and browse products they want to buy, and add products to their shopping cart to place an order. we have 3 Order Method.
</div>

## 🖥️ Tech Stack
**Frontend:**

**package manager**

![Yarn](https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white)

- **Show Error:** [Toastify](https://www.npmjs.com/package/react-toastify)           <br/>
- **Data Fetch from Backent:** [axios](https://www.npmjs.com/package/axios)   <br/>
- **Icons:** [react-icons](https://react-icons.github.io/react-icons/)   <br/>
- **Payment stripe:** [Strip](https://dashboard.stripe.com/login?redirect=%2Ftest%2Fpayments)   <br/>
- **Payment Paypal:** [Strip](https://www.paypal.com/in/home)   <br/>
- **Store Date in Cookes:** [js-cookie](https://www.npmjs.com/package/js-cookie)   <br/>
- **Sand maill to User,seller,Admin:** [nodemailer](https://www.npmjs.com/package/nodemailer)   <br/>
- **Store Img in Local Dev:**  [multer](https://www.npmjs.com/package/multer)

## 🚀 Features

- User Authentication Pages 🚪
  - User Signup 📝
    - email verification
    - upload a Profile image
  - User Login 🔐
- Home Page 🏠
  - View all product uploads by seller 📃
  - filter with the category 📊
  - Best-selling product (Sort by Sold_out data) 💎
  - All Product 📦
  - All Event's 🎊
  - FAQ 🙋
- Filters for Sorting Posts 🗂️
  - Sort posts by Clothes, Shows, gifts, etc...
- User Search Bar 🔍
  - Search for product 🔎
  - Click on a user to go to the Product details page 👤
- wish list ❤️
  - store in cart 👀
- Add to cart 🛒
  - Check out for payment 💳
    - we have 3 payment systems **Pay-pal**,**Strip**,**Cash of Delivery (COD)**
- Apply Coupon Code for Discount 👉💥
- Product Explore Page 🔍
  - View Product from another seller 🌍
  - View reviews from other users ⭐
  - The eye button shows Product Details 👁
  - Original Price and discount price 💵
  - HowMeney Buy this product  🤝
  - Inc and Dec product  📉 +
  - Show Description of product 📃
  - View Seller Profile 👥
  - Chating with Seller 💬
  - Show Seller Information 📋
  - Show Related Products 🔗
  - Add to wish list ❤️
  - Add to Cart  🛒
- User Profile Page 👤
  - Edit your profile details - profile photo, name, email, phone number ✏️
  - change Password 🔐
  - View All Order 👨🏾‍💻.
  - After Delivery of the product user can Refund the product. 🔙
  - User inbox Chat with the seller. ✉️
  - Use can Track Orders. 🛤️
  - Store 3 Address Details. Like Default, Home, office. 📫
  - **Only Admin show Admin Dashboard** 👑
  - Logout 🔚
  - Create a Review After Delivery Product 🚛
  - After the Buy product is Sold out is increased. and Stock decrease in DB.

- Message ✉️
  - Sand Image 🖼️
  - Show active or not 🟢
  - Time of sand Message ⏰
- Popular Events 💥
  - Show Recent Events
- Responsive 📱
  - All screens are responsive
- Alerts 🚨
  - Alerts in the app to notify users about success/failure operations
- Seller Authentication Pages 🚪
  - Seller Signup 📝
    - shop name, Phone Number, Email address, Address,Zip Code, Password ✍
    - upload a Profile image 📷
    - email verification ✅
  -  Seller Login 🔐
- Seller Dashboard 👨🏻‍🔧
  - Overview of a Product and Latest Orders 🖇️
  - Account Balance (with 10% service charge) 💰
- All Orders ⚖
   - Seller Update Product Delivery status 📆
  - Create Products  ✔️
     - name*
     - Description *
     - Category *  like:- Computer and Laptops, Cosmetics and body care, Accessories, clothes,Shoes, Gifts, Pet Care, Mobile and Tablets, Music and Gaming, Other 🧩
  - All product 💻
     - Seller can delete Product ❌
    - View all Products 📦
 - Create an Event  💥🎉
    - name* 📇
   - Description *
   - Category *  like:- Computer and Laptops, Cosmetics and body care,Accessories, Clothes, Shoes,Gifts, Pet Care, Mobile and Tablets, Music and Gaming, Other
   - Tags
   - Original Price
   - Price (With Discount) *
   - Product Stock *
   - Event Start Date * ✅
   - Event End Date * (Default 3 days) ⛔
   - Upload multiple Images * 📷
- All Event 🎉
  - Show Event 💥
  - Delete Event  ⛔
- Withdraw Money 📥
  - Add Bank Details 🏛️
  - Not withdraw the highest amount of Balance 💱
  - Sand mail to sell with amount 📩
  - Delete Bank Details 🪧
- Shop Inbox 📞
    - All Messages 📬
    - Sand Image to user 🖼️
    - Show Activ function 🟢
- Discount Codes 🎟️
  - Create coupon code 🖱
  - Delete coupon code 🛑
  - apply all Products of the shop  🤩
  - Can apply the specific product 1️⃣☝️
- Refunds 🔙
  - Seller can update the Status of the Product 🔄
- Settings ⚛
  - update Images, Shop Address, Shop Phone Number, Shop Zip Code ⛓
  - Add Shop description 📖
- Shop Desboard 🎰
   - Shop Products 🌃
   - Running Events 🎪
   - Shop Reviews ⭐
   - Log out  ↪️
- Admin Authentication Pages (normal user in DB roll in Admin) 🚪
   - Admin Signup 📝
   - Admin Login 🔐
  - Overview 👔
        - Total Earning 🤑
        - All Sellers 👨‍🔧
        - All Orders 🛍️
        - Latest Orders 🔢
  - Show All Orders of Seller's 🛍️
  - Show All sellers and Delete ⛔
  - Show All users and Delete 👨‍👩‍👦‍👦 ⛔
  - All Products in DB. 👨🏻‍💻
  - All Events of Seller 📢
  - verify  Seller Withdraw request and Sand mail to update's 📧
  - if Delete images it also deletes from the local devise

## 📹 Video Demo



## File structure
#### `client` - Holds the client application
- #### `public` - This holds all of our static files
- #### `src`
    - #### `assets` - This folder holds assets such as images, docs, and fonts
    - #### `components` - This folder holds all of the different components that will make up our views
      - Admin
      - cart
      - Checkout
      - Events
      - layout
      - Logout
      - Payment
      - Products
      - Profile
      - Route
      - Shop
      - Signup
      - Wishlist
     - #### `pages` - This folder holds All pages Admin, shop, user
       - Shop
     - #### `redux` - This folder holds all states of the Web app
       - action
       - reducer
     - #### `static` - This folder holds Static file like logo categorie
    - #### `App.js` - This is what renders all of our browser routes and different views
    - #### `index.js` - This is what renders the react app by rendering App.js, should not change
- #### `package.json` - Defines npm behaviors and packages for the client
#### `server` - Holds the server application
- #### `config` - This holds our configuration files, like mongoDB uri
- #### `controller` - These hold all of the callback functions that each route will call
- #### `db` - These hold all of Data Base Connection
- #### `middleware` - These hold all error handle
- #### `models` - This holds all of our data models
- #### `uploads` - Store all image in hear
- #### `utils` - This holds all of our HTTP to URL. jwtToken and sand mail, Token gentrare
- #### `mlter.js` - Sand mail login
- #### `server.js` - Defines npm behaviors and packages for the client
- #### `package.json` - Defines npm behaviors like the scripts defined in the next section of the README
#### `socket` - Socket.io is use to chaing feacher
  - .env
  - index.js
  - package.json
#### `.gitignore` - Tells git which files to ignore
#### `README` - This file!

---

💻 How to run the app locally! 🏃

### STAP-1

### STAP-2
- `cd frontend`
- `yarn install`
- `yarn start`

### STAP-3
- `cd backend`
- `yarn install`
- create folder `uploads`
- create `confilg` folder and a `.env` file
- use your Cradincial in.env file

```
PORT = 8000
DB_URL = ""
JWT_SECRET_KEY = ""
JWT_EXPIRES = 7d
ACTIVATION_SECRET =
SMPT_HOST = 'smtp.gmail.com'
SMPT_PORT = 465
SMPT_PASSWORD =
SMPT_MAIL =
STRIPE_API_KEY =
STRIPE_SECRET_KEY =
```
- `yarn start`

### STAP-4

- `cd socket`
- `yarn install`
- create a `.env` file
```
PORT = 4000
```
- `yarn start`
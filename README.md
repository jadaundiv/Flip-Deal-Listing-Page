# FlipDeal Product Listing Page

This project is a backend implementation for FlipDeal's Product Listing Page. It allows users to sort and filter products based on various criteria such as popularity, price, RAM, ROM, brand, and OS.

## Features

1. **Sort Products**:
   - By Popularity (Rating)
   - By Price (High to Low)
   - By Price (Low to High)

2. **Filter Products**:
   - By RAM
   - By ROM
   - By Brand
   - By OS
   - By Price

3. **Get All Products**: Fetch the original list of products.

## API Endpoints

1. **Sort by Popularity**
   - Endpoint: `/products/sort/popularity`
   - Example: `http://localhost:3000/products/sort/popularity`
   - Output: JSON of products sorted by rating (high to low)

2. **Sort by Price (High to Low)**
   - Endpoint: `/products/sort/price-high-to-low`
   - Example: `http://localhost:3000/products/sort/price-high-to-low`
   - Output: JSON of products sorted by price (high to low)

3. **Sort by Price (Low to High)**
   - Endpoint: `/products/sort/price-low-to-high`
   - Example: `http://localhost:3000/products/sort/price-low-to-high`
   - Output: JSON of products sorted by price (low to high)

4. **Filter by RAM**
   - Endpoint: `/products/filter/ram`
   - Parameter: `ram` (e.g., `8`)
   - Example: `http://localhost:3000/products/filter/ram?ram=8`
   - Output: JSON of products with the specified RAM

5. **Filter by ROM**
   - Endpoint: `/products/filter/rom`
   - Parameter: `rom` (e.g., `128`)
   - Example: `http://localhost:3000/products/filter/rom?rom=128`
   - Output: JSON of products with the specified ROM

6. **Filter by Brand**
   - Endpoint: `/products/filter/brand`
   - Parameter: `brand` (e.g., `apple`)
   - Example: `http://localhost:3000/products/filter/brand?brand=apple`
   - Output: JSON of products with the specified brand

7. **Filter by OS**
   - Endpoint: `/products/filter/os`
   - Parameter: `os` (e.g., `android`)
   - Example: `http://localhost:3000/products/filter/os?os=android`
   - Output: JSON of products with the specified OS

8. **Filter by Price**
   - Endpoint: `/products/filter/price`
   - Parameter: `price` (e.g., `30000`)
   - Example: `http://localhost:3000/products/filter/price?price=30000`
   - Output: JSON of products with price <= specified value

9. **Get All Products**
   - Endpoint: `/products`
   - Example: `http://localhost:3000/products`
   - Output: JSON of all products

## How to Run

1. Clone the repository.
2. Install dependencies: `npm install`.
3. Start the server: `node app.js`.
4. Access the APIs at `http://localhost:3000`.

## Frontend Integration

The backend APIs are designed to be integrated with FlipDeal's frontend UI. Update the API URLs in the frontend code to point to the deployed backend.

## Live Demo

Check out the live demo of the frontend: [FlipDeal Product Listing Page](https://bd2-listing-page.vercel.app/).

---

Developed by Divyanshu Jadaun for FlipDeal.

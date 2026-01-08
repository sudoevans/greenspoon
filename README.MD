# Greenspoon Kenya Product Dataset

This repository contains structured product data scraped from [Greenspoon Kenya](https://greenspoon.co.ke), an online grocery and lifestyle store.

The dataset is provided in two formats:

- **JSON** – Suitable for developers working with APIs, automation scripts, or NoSQL databases.
- **CSV** – Suitable for analysts using spreadsheets, SQL databases, or data visualization tools.

---

## Data Format

### JSON Example

```json
{
  "product_name": "Fresh Hass Avocado - 2 Pieces",
  "product_url": "https://greenspoon.co.ke/product/fresh-hass-avocados",
  "image_url": "https://greenspoon.co.ke/wp-content/uploads/2025/12/Greenspoon-83-720x480.jpg",
  "price": "KES 199",
  "category": "Fruits & Vegetables",
  "is_in_stock": true
}
````

### CSV Example

```csv
product_name,product_url,image_url,price,category,is_in_stock
Fresh Hass Avocado - 2 Pieces,https://greenspoon.co.ke/product/fresh-hass-avocados,https://greenspoon.co.ke/wp-content/uploads/2025/12/Greenspoon-83-720x480.jpg,KES 199,Fruits & Vegetables,true
```

---

## Fields

* **product_name**
  Name of the product as listed on Greenspoon.

* **product_url**
  Direct link to the product page.

* **image_url**
  URL of the product image.

* **price**
  Current listed price in Kenyan Shillings (KES).

* **category**
  Product category such as Bakery, Dairy, or Fruits & Vegetables.

* **is_in_stock**
  Boolean value indicating whether the product is available.

---

## Usage

This dataset can be used for:

* E-commerce analysis, including price and availability tracking
* Data visualization and reporting
* Automation workflows and monitoring tools
* Search, filtering, and category-based queries

---

> [!NOTE]
> - The data is scraped for educational and research purposes.  
> - Prices and availability may change frequently. Regular updates are recommended.  
> - Ensure compliance with Greenspoon’s [Terms of Service](https://greenspoon.co.ke) when using this dataset.  

---

## Contribution

Contributions are welcome. You may submit pull requests for:

* Data updates
* New fields
* Improvements or corrections

Please open an issue or submit a pull request as appropriate.

---

## License

This project is licensed under the terms described in the [LICENSE](LICENSE) file.


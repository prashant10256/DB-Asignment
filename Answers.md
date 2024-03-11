Q.1) Explain the relationship between the "Product" and "Product_Category" entities from the above diagram.

ans =>
The relationship between the "Product" and "Product_Category" entities is established through the "category_id" field in the "product_inventory" table. This field acts as a foreign key, linking each product to a specific product category.

Q.2) How could you ensure that each product in the "Product" table has a valid category assigned to it?

ans =>
To ensure that each product in the "Product" table has a valid category assigned to it, you can use a foreign key constraint. This constraint should be applied to the "category_id" field in the "product_inventory" table, referencing the "id" field in the "Product_Category" table. This way, any attempt to insert a product with an invalid category ID will result in a constraint violation, ensuring data integrity.

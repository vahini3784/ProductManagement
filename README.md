# ProductManagement
Description:
ProductManagement Which can have Categories and Products.
User can create and view list of categories.
User can manage products.
User can add/remove products to/from category.
There are 4 layers :
  1. View : 
     In View we need to handle the following requirements:
    -> CategoryManagement: 1.Create category
                           2.View category(show products)
    ->Product Management: 1.Create product
                          2.Delete product
                          3.Update product
  2.Service : This is the Wrapper class for DAO. 
  3.DAO:  By using this class we can interact with DataBase.
  4.DataBase: By using this class we can create Tables.
  

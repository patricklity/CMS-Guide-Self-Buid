************
Product Inventory Module 
************
Product Inventory Module displays the Inventory details of different Products in a table. Users can Search or Export Inventory details of different products by clicking on the buttons on top of the Product Inventory table.

|Productinventorymodule|

.. list-table:: Product Inventory Module
    :widths: 10 50
    :header-rows: 1
    :stub-columns: 1

    * - FIELD NAME
      - FIELD DESCRIPTION
    * - Product Code
      - The Product Code
    * - Default Barcode
      - The Default Barcode of The Product
    * - Category
      - The Category of The Product
    * - Brand
      - The Product Brand
    * - Product Name(Eng)
      - The English Product Name
    * - Product Name(Chi)
      - The Chinese Product Name
    * - SOH(N)
      - The fields state the normal stock on hand. Normal stock means that the best before date deducts min shelf day and deducts 10 days (for delivery process) is after today
    * - SOH(C)
      - The fields state the clearance stock on hand. Clearance stock means that the best before date between today plus 10 days (for delivery process) and today plus 10 days (for delivery process) plus min shelf day.
    * - SOH(E)
      - The fields state the expired stock on hand. Expired stock means that the best before date less than today plus 10 days (for delivery process).
    * - SOH(H)
      - stock on hand - Hold
    * - Total SOH
      - sum of all stock on hand (Normal + Clearance + Expired)
    * - Status
      - Active/ Inactive Inventory


Buttons
==================  
Users can search and export Inventory details of different Products by clicking the buttons on top of the Product Inventory table.

|Productinventorybuttons|

.. list-table:: Product Inventory Module Buttons
    :widths: 10 50
    :header-rows: 1
    :stub-columns: 1

    * - FIELD NAME
      - FIELD DESCRIPTION
    * - Advanced Search
      - Users can search for Inventory details by different criterion
    * - Export Excel
      - Users can export Inventory Details of different Products 
    * - Search SN/ Barcode/ Product Name Input Box
      - User can carry out quick search by inputting the related values into the Input Box
   

.. |Productinventorymodule| image:: Productinventorymodule.JPG
.. |Productinventorybuttons| image:: Productinventorybuttons.JPG

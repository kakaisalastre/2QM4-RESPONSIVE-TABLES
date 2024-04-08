# 2QM4-RESPONSIVE-TABLES
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-KyZXEAg3QhqLMpG8r+Knujsl7/1L_dstPt3HV5HzF6Gvk/e9T9hXmJ58bldgTk+" crossorigin="anonymous">
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 2rem;
        }

        h1 {
            text-align: center;
            margin-bottom: 3rem;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th,
        td {
            padding: 0.75rem;
            border: 1px solid #dddddd;
        }

        th {
            background-color: #fff5f5;
            font-weight: bold;
        }

        tr:nth-child(even) {
            background-color: #f2f2f233;
        }

        @media (max-width: 767.98px) {
            h1 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Restaurant Menu</h1>
        <table>
            <thead>
                <tr>
                    <td>Invoive</td>
                    <td>Customer Name</td>
                    <td>Ship</td>
                    <td>Item Name</td>
                    <td>Description</td>
                    <td>Price</td>
                    <td>Purchased Price</td>
                    <td>Status</td>
                </tr>
                <tr>
            </thead>
            <tbody>
                <tr>
                    <td>001</td>
                    <td>Trisha</td>
                    <td>Korea</td>
                    <td>Classic Eggs Benedict</td>
                    <td>Poached eggs and Canadian bacon on toasted English muffins, topped with hollandaise sauce and served with a side of breakfast potatoes.</td>
                    <td>$25.99</td>
                    <td>$22.00</td>
                    <td>Deliver</td>
                </tr>
                <tr>
                <tr>
                     <td>002</td>
                     <td>Popoy</td>
                     <td>Las Pinas</td>
                     <td>Chocolate Lava Cake</td>
                     <td>Rich and decadent chocolate cake with a molten chocolate center, served warm</td>
                     <td>$21.99</td>
                    <td>$20.00</td>
                    <td>Deliver</td>
                 </tr>
                 <tr>  
                <tr>
                     <td>003</td>
                     <td>Basya</td>
                     <td>Las Pinas</td>
                     <td>Apple Cinnamon Pancakes</td>
                    <td>Fluffy pancakes made with fresh apples and cinnamon, served with maple syrup.</td>
                    <td>$18.99</td>
                    <td>$11.00</td>
                    <td>Deliver</td>
                </tr>
                 <tr>
                 <tr>
                     <td>004</td>
                    <td>Anj</td>
                    <td>Las Pinas</td>
                    <td>Crab Stuffed Avocado</td>
                     <td>Half an avocado filled with a creamy crab salad, served with a side of mixed greens.</td>
                     <td>$10.99</td>
                     <td>$8.00</td>
                    <td>Deliver</td>
                 </tr>
                <tr>
                    <tr>
                        <td>005</td>
                        <td>Henry</td>
                        <td>Cavite</td>
                        <td>Sizzling Garlic Shrimp</td>
                        <td>Plump shrimp sautéed with garlic, butter, and a hint of chili flakes, served sizzling hot.</td>
                        <td>$15.99</td>
                       <td>$12.00</td>
                       <td>Processing</td>
                    </tr>
                    <tr>    
                    <tr>
                        <td>006</td>
                        <td>Elezar</td>
                         <td>Cavite</td>
                         <td>Spicy Tofu Stir-Fry </td>
                         <td>Cubes of tofu stir-fried with mixed vegetables in a spicy sauce, served over steamed rice.</td>
                         <td>$21.99</td>
                        <td>$19.00</td>
                         <td>Processing</td>
                   </tr>
                  <tr>  
                 <tr>
                        <td>007</td>
                        <td>Shanin</td>
                        <td>Molino</td>
                        <td>Decadent Chocolate Lava Cake</td>
                        <td> Rich chocolate cake with a molten chocolate center, served warm with a scoop of vanilla ice cream.</td>
                        <td>$18.99</td>
                       <td>$16.00</td>
                       <td>Processing</td>
                    </tr>
                    <tr>  
                 <tr>
                        <td>008</td>
                         <td>Irish</td>
                        <td>Korea</td>
                        <td>Mango Tango Chicken</td>
                        <td>Grilled chicken breast topped with a tangy mango salsa, served with rice pilaf.</td>
                         <td>$25.99</td>
                         <td>$24.00</td>
                        <td>Processing</td>
                  </tr>
                <tr>   
                 <tr>
                        <td>009</td>
                        <td>RL</td>
                        <td>Las Pinas</td>
                        <td>Apple Cinnamon Pancakes</td>
                        <td>Fluffy pancakes made with fresh apples and cinnamon, served with maple syrup.</td>
                        <td>$29.99</td>
                       <td>$24.00</td>
                       <td>Processing</td>
                    </tr>
                    <tr> 
                  <tr>
                          <td>010</td>
                        <td>Axel</td>
                         <td>Pilar</td>
                         <td>Smoked Salmon Eggs Benedict </td>
                         <td> Poached eggs and smoked salmon on an English muffin, topped with hollandaise sauce, served with breakfast potatoes.</td>
                         <td>$23.99</td>
                        <td>$21.00</td>
                         <td>Processing</td>
                 </tr>
                <tr>  
                    <tr>
                        <td>011</td>
                        <td>Melo</td>
                        <td>Pilar</td>
                        <td>Pesto and Sun-Dried Tomato Pasta </td>
                        <td> Linguine tossed in a basil pesto sauce with sun-dried tomatoes and Parmesan cheese.</td>
                        <td>$23.99</td>
                       <td>$22.00</td>
                       <td>Processing</td>
                    </tr>
                    <tr>  
                  <tr>
                        <td>012</td>
                         <td>Christhyl</td>
                         <td>Las Pinas</td>
                         <td>Steak Frites</td>
                        <td>Grilled hanger steak served with crispy French fries and a side of garlic aioli for dipping.</td>
                         <td>$10.00</td>
                         <td>$7.00</td>
                         <td>Processing</td>
                 </tr>
                <tr>  
                    <tr>
                        <td>013</td>
                        <td>Christine</td>
                        <td>Cavite</td>
                        <td>Vegetarian Tacos</td>
                        <td>Corn tortillas filled with black beans, roasted corn, bell peppers, avocado, and cilantro-lime crema.</td>
                        <td>$15.00</td>
                       <td>$14.78</td>
                       <td>Processing</td>
                    </tr>
                    <tr>  
                  <tr>
                        <td>014</td>
                        <td>Ed</td>
                        <td>Bacoor</td>
                         <td>Steak Frites</td>
                         <td>Grilled hanger steak served with crispy French fries and a side of garlic aioli for dipping.</td>
                         <td>$26.00</td>
                        <td>$25.99</td>
                        <td>Processing</td>
                 </tr>
                 <tr> 
                    <tr>
                        <td>015</td>
                        <td>Agri</td>
                        <td>Laguna</td>
                        <td>Lemon Garlic Butter Scallops</td>
                        <td>Plump scallops seared to perfection in a lemon garlic butter sauce, served over a bed of creamy risotto.</td>
                        <td>$10.00</td>
                       <td>$9.00</td>
                       <td>On hold</td>
                    </tr>
                    <tr>  
                        <tr>
                            <td>016</td>
                            <td>Kakai</td>
                            <td>Laguna</td>
                            <td>Truffle Mushroom Risotto</td>
                            <td>Creamy risotto cooked with a medley of wild mushrooms and finished with truffle oil and Parmesan cheese.</td>
                            <td>$15.00</td>
                           <td>$14.00</td>
                           <td>Processing</td>
                        </tr>
                        <tr>  
                     <tr>
                             <td>017</td>
                            <td>Mina</td>
                            <td>Las Pinas</td>
                            <td>Crispy Brussels Sprouts</td>
                            <td>Brussels sprouts fried to a crisp and tossed in a balsamic glaze, topped with Parmesan cheese.</td>
                             <td>$25.00</td>
                            <td>$24.00</td>
                             <td>Deliver</td>
                     </tr>
                    <tr>  
                        <tr>
                            <td>018</td>
                            <td>Carl</td>
                            <td>Las Pinas</td>
                            <td>Sesame Ginger Glazed Salmon</td>
                            <td>Grilled salmon fillet glazed with a sweet and savory sesame ginger sauce, served with jasmine rice and steamed broccoli.</td>
                            <td>$25.98</td>
                           <td>$24.00</td>
                           <td>Deliver</td>
                        </tr>
                        <tr>  
                     <tr>
                            <td>019</td>
                             <td>Ella</td>
                             <td>Bacoor</td>
                             <td>Blackened Shrimp Tacos</td>
                             <td> Blackened shrimp served in warm tortillas with avocado, cabbage slaw, and chipotle aioli.</td>
                             <td>$12.99</td>
                            <td>$11.00</td>
                             <td>Processing</td>
                     </tr>
                     <tr>  
                        <tr>
                            <td>020</td>
                            <td>Allysa</td>
                            <td>Pilar</td>
                            <td>Pulled Pork Sliders</td>
                            <td>Slow-cooked pulled pork tossed in barbecue sauce and served on mini brioche buns with coleslaw.</td>
                            <td>$20.00</td>
                           <td>$19.00</td>
                           <td>Processing</td>
                        </tr>
                        <tr>                          

            </tbody>
        </table>
    </div>
</body>

</html>

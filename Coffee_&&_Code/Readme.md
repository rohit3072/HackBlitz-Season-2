problem Statement :-
EcoSwap - Web-Based Sustainable Product Exchange Platform
Domain: Web App, Sustainability, Marketplace
Develop a web application that facilitates the exchange or donation of gently used items like clothes, books, and electronics, promoting circular economy. explain this problem statement in simple terms

Explanation :- 
Your website, **EcoSwap**, is a donation-based platform where users can browse donated items, view their details, and claim them. It consists of three main pages: `products.html`, `details.html`, and `messages.html`.  

The **`products.html`** page serves as the homepage, displaying a list of donated items such as chairs, tables, and sofas. Each item is presented in a Bootstrap-styled card with an image, category, and a **"Claim Item"** button. When a user clicks the button, they are redirected to the `details.html` page with item details passed as **URL parameters** (e.g., name, image, category, donor).  

The **`details.html`** page extracts these parameters and dynamically displays the product’s name, image, description, donor details, and pickup location. It includes a **"Claim Item"** button that, when clicked, redirects the user to `messages.html` while passing relevant product details. This allows the user to proceed with claiming the item by contacting the donor.  

Finally, the **`messages.html`** page contains a contact form where the user can enter their name, email, and an optional message for the donor. When submitted, the form displays a success message, confirming that the inquiry has been sent. The entire website uses **Bootstrap for styling**, **JavaScript for dynamic content updates**, and **URL parameters to manage product data across pages**, making it a smooth and interactive donation platform.

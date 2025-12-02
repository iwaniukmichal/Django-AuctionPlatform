# Django Auction Platform

A web-based auction platform built with Python and the Django framework. Users can create auction listings, place bids on items, and add comments.

## Features

*   **User Authentication**: Secure user registration and login system.
*   **Create Listings**: Authenticated users can create new auction listings, including a title, description, starting bid, and an optional image.
*   **Active Listings**: View all currently active auction listings on a single page.
*   **Item Details**: Click on any auction to see its full details, including the current price, description, and any comments.
*   **Bidding**: Logged-in users can place bids on active auctions. The bid must be higher than the current price.
*   **Commenting**: Users can leave comments on any auction item's page.
*   **Categorization**: Listings can be assigned to categories for easier browsing.
*   **User Profile**: A personal page where users can view the auctions they have created.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   Python 3.x
*   pip (Python package installer)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/Django-AuctionPlatform.git
    cd Django-AuctionPlatform
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Apply database migrations:**
    ```bash
    python manage.py migrate
    ```

5.  **Create a superuser to access the admin panel:**
    ```bash
    python manage.py createsuperuser
    ```

6.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

7.  Open your web browser and navigate to `http://127.0.0.1:8000/` to see the application in action.

**Note**: Replace `your-username` in the clone URL with the actual username if you are cloning from a fork.
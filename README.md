# TextUtils 📝

TextUtils is a Django-based web application designed to help users analyze and manipulate text efficiently. Whether you need to remove punctuation, capitalize text, or clean up extra spaces, TextUtils has you covered.

## 🚀 Features

- **Remove Punctuations**: Strips all punctuation marks from the text.
- **UPPERCASE**: Converts the entire text to uppercase.
- **New Line Remover**: Removes all new lines, converting the text into a single line.
- **Extra Space Remover**: Removes extra spaces between words, ensuring clean formatting.

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap 5
- **Database**: SQLite (Default Django DB)

## ⚙️ Installation & Setup

Follow these steps to set up the project locally:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/sayan110923/TextUtils.git
    cd TextUtils
    ```

2.  **Create a virtual environment (Optional but Recommended)**
    ```bash
    python -m venv venv
    # Windows
    .\venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Apply Migrations**
    ```bash
    python manage.py migrate
    ```

5.  **Run the Server**
    ```bash
    python manage.py runserver
    ```

6.  **Access the App**
    Open your browser and go to `http://127.0.0.1:8000/`

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.


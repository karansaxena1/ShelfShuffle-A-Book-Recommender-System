# 📚 ShelfShuffle: A Book Recommender System  

**ShelfShuffle** is a book recommendation system built using **Collaborative Filtering**. It helps users discover books based on user preferences and similarities in reading patterns.  

---
![Screenshot 2025-02-15 121232](https://github.com/user-attachments/assets/7f9af634-ee3a-41fb-b40b-153b5efb67c2)
![Screenshot 2025-02-15 121353](https://github.com/user-attachments/assets/7d7d527a-0550-4ca0-ab90-c80725ff1f1c)

## Working Link 
https://shelfshuffle.onrender.com/

## 🚀 Features  
✅ Popularity-Based Recommendations (Top-rated books)  
✅ Collaborative Filtering (Finds books similar to user-selected books)  
✅ Interactive Web Interface (Built with Flask)  
✅ Efficient Search & Recommendation using Cosine Similarity  

---

## 📂 Dataset  
The system uses three datasets:  
- **Books.csv** → Contains book details (Title, Author, ISBN, etc.)  
- **Users.csv** → Contains user details (User-ID, Location, Age)  
- **Ratings.csv** → Contains book ratings (User-ID, ISBN, Rating)  

---

## 🏗 Tech Stack  
- **Python** (Flask, Pandas, NumPy, Scikit-Learn)  
- **Machine Learning** (Collaborative Filtering with Cosine Similarity)  
- **Frontend** (HTML, CSS)  
- **Data Storage** (Pickle for precomputed recommendations)  

---

## 🎯 How It Works  
1. **Popularity-Based Recommendations:**  
   - Books with the most ratings and highest average ratings are displayed.  
2. **Collaborative Filtering:**  
   - Builds a user-item matrix using **Pivot Tables**.  
   - Calculates **Cosine Similarity** between books.  
   - Suggests books similar to the user’s selected book.  

---

## 🛠 Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/ShelfShuffle.git
cd ShelfShuffle
```
## 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
## 3️⃣ Run the Flask App
```bash
python app.py
```
## 4️⃣ Open in Browser
```cpp
http://127.0.0.1:5000/
```

## 📌 Usage
**Homepage (/) → Displays popular books.**

**Recommendation Page (/recommend) → Users enter a book title to get similar recommendations.**

## 🎯 Future Improvements
**🔹 Add content-based filtering for better recommendations.**

**🔹 Implement user authentication and personalized book lists.**

**🔹 Improve UI/UX for better user experience.**

## 📝 License
This project is open-source under the MIT License.

## 👨‍💻 Developed with ❤️ by Karan Saxena
🔗 GitHub: https://github.com/karansaxena1
📧 Contact: karan.saxena1362@gmail.com

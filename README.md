# -Vibe_Matcher
 Vibe Matcher - Product Recommendation Based on Text Query Find products that match the "vibe" of a user's query using TF-IDF and cosine similarity. 
 """
Vibe Matcher - Product Recommendation Based on Text Query

Author: Isha Santosh Khadke
Purpose: Find products that match the "vibe" of a user's query using TF-IDF and cosine similarity.

How it works:
1. Converts a user's text query into a TF-IDF vector.
2. Computes cosine similarity with precomputed product embeddings.
3. Selects top-k products with the highest similarity scores.
4. Returns a DataFrame with product details and similarity scores.
5. Flags a fallback if the highest similarity is below a given threshold.

Dependencies:
- pandas
- numpy
- scikit-learn (for TF-IDF and cosine_similarity)

Usage Example:
results, fallback = vibe_match("cool summer dress", top_k=5, threshold=0.35)
"""

<img width="1066" height="526" alt="image" src="https://github.com/user-attachments/assets/7c3d021c-dc8b-4fde-945d-e06a6d231e28" />
<img width="962" height="517" alt="image" src="https://github.com/user-attachments/assets/a1f704ca-6813-4fc2-9949-cd58fd22d8f6" />
<img width="996" height="533" alt="image" src="https://github.com/user-attachments/assets/2cdf9306-0c1e-4476-bd7b-46287bb3c5a7" />


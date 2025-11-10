I built this project as part of the Nexora internship assignment. The main idea behind it was to create a “Vibe Matcher” — a simple yet powerful recommendation system that can understand text-based vibes and find the most relevant matches from a dataset.

Instead of using the OpenAI text-embedding-ada-002 model (which needs API access), I used local sentence-transformer embeddings to make the system lightweight, fast, and completely offline-friendly. This also helps avoid API quota or key issues while maintaining good semantic understanding.

In this notebook, I’ve clearly explained every step — from data cleaning and preprocessing to embedding generation, similarity calculations, and final recommendations. The project is structured so that anyone can easily follow, modify, or scale it further.

My goal was to make the model both practical and efficient, while keeping it accessible to everyone without relying on paid APIs.
# Nexora-Internship-Assignment
Create a mini recommendation system that matches a vibe-based text query (like “boho outfit for summer”) with fashion products described in text. Each product is embedded into a vector space using a text embedding model, and we use cosine similarity to find the top-3 most relevant matches.

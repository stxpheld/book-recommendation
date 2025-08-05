# Build a Book Recommender with LLMs 

développement d’un moteur de recommandation de livres intelligent en Python basé sur des modèles de langage (LLM), avec les fonctionnalités suivantes :

Nettoyage des données textuelles (data-exploration.ipynb)

Recherche sémantique par similarité de sens via une base vectorielle, permettant de retrouver les livres les plus proches d’une requête en langage naturel (vector-search.ipynb)

Classification zéro-shot (fiction / non-fiction) grâce aux LLM, pour filtrer les livres selon leur type (text-classification.ipynb)

Analyse de sentiments et d’émotions, pour trier les livres selon leur tonalité (suspense, joie, tristesse, etc.) (sentiment-analysis.ipynb)


Les données utilisées proviennent de Kaggle, avec également des indications dans le dépôt sur la procédure à suivre pour les télécharger.


Ce projet a été initialement développé en Python 3.11. Pour le faire fonctionner, les dépendances suivantes sont nécessaires :

* [kagglehub](https://pypi.org/project/kagglehub/)
* [pandas](https://pypi.org/project/pandas/)
* [matplotlib](https://pypi.org/project/matplotlib/)
* [seaborn](https://pypi.org/project/seaborn/)
* [python-dotenv](https://pypi.org/project/python-dotenv/)
* [langchain-community](https://pypi.org/project/langchain-community/)
* [langchain-opencv](https://pypi.org/project/langchain-opencv/)
* [langchain-chroma](https://pypi.org/project/langchain-chroma/)
* [transformers](https://pypi.org/project/transformers/)
* [gradio](https://pypi.org/project/gradio/)
* [notebook](https://pypi.org/project/notebook/)
* [ipywidgets](https://pypi.org/project/ipywidgets/)


L’ensemble des dépendances est listé dans le fichier requirements.txt inclus dans le dépôt.


# FastAttack
An adversarial attack method against text classifiers which uses FastText Embeddings for transformations.
<a href="https://colab.research.google.com/drive/1Qe7yGcxQPg5vqDijB97yedMOonH1vyhg?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

To run: Using Google Colab with GPU runtime is recommended. It will help you save time by not installing a ton of dependencies!

1. Make a copy of the FastAttack-models folder from https://drive.google.com/drive/folders/1izR5sO08up0LJ3-g7qtO30iHfNnaxFAU?usp=sharing to your drive.

2. Open FastAttack.ipynb on Colab.

3. Load fasttext.model by changing the path appropriately.

4. The target models and datasets can be changed at the locations pointed in the notebook. List of available models and datasets is available here:                https://textattack.readthedocs.io/en/latest/3recipes/models.html#available-models

5. Run the attack for a certain number of examples. The attack results and a summary will be printed on the console.

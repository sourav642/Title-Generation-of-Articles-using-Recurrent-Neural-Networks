## WebApp

* This Folder contains Jupyter Notebook for running the WebApp for Title Generation
* This WebApp is created using `flask-ngrok` which allows hosting a public IP thorugh Jupyter Notebook
* The WebApp generates a public IP which is accessible through any device while the cell is running.
* This WebApp contains two pages,
  * **Generate Title** - Here users can submit an abstract and our model will suggest the Suitable Title for this
  *  **Evaluate Title** - Here users can submit their abstract along with the Title in their mind, our model will Generated the suitable title for that abstract and compare with the title user has given and also displays the similarity in [BLEU](https://en.wikipedia.org/wiki/BLEU) score
  * We have also added a _Pick Random Article_ feature, using which users can pick a random article quickly for testing   
* Before Running the cells make sure,
  * The Model (with attention) is already trained and the stored weights are available
  * The Test datasets are present in Dataset folder
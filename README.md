Hi there and welcome, 

to the imdb social media anlytics project. 

If all you want is to see a fully running version of the project you can just go to thse google colab notebooks, and you can skip the rest of the this. As the current database is in a google cloud instance that should be up till the end of june. So have fun.

(for the role graphs alreayd computed you)
[https://colab.research.google.com/drive/1csfqn1xTlyIWZ-GMCaJWRi2QkFpmNwov?usp=sharing
](https://colab.research.google.com/drive/1BHW-KMkFT6icX2n19DW9rPat3dGUJUCd?usp=sharing)

(for the ego graphs already computed for you)
[https://colab.research.google.com/drive/1csfqn1xTlyIWZ-GMCaJWRi2QkFpmNwov?authuser=1#scrollTo=xmGnVihkcIPC
](https://colab.research.google.com/drive/1csfqn1xTlyIWZ-GMCaJWRi2QkFpmNwov?authuser=1#scrollTo=xmGnVihkcIPC)

The break down of the important parts is rather simple

First run this to get data from imdb : cinemagoer_get_people.ipynb 

Then with data from above combined with the kaggle dataset generate a graphml file  : neo4j_generate_graphdb.ipynb 

Import the graphml file into neo4k  : https://neo4j.com/labs/apoc/4.1/import/graphml/

Gets data from the neo4j database : neo4j__temporal_slicer_v3.ipynb 



this last part needs the right credentials to access the google cloud version of the database :  Neo4j-student-project_credentials.txt 


also yes I know bad practice to put the database credentials here but since this is for a baby sutdent project on free trial, and google says 

"When the Free Trial ends, all resources you created during the trial are stopped, and you will not be charged, unless you upgrade to a paid Cloud Billing account"

so I think i'll live. 

these arent really important and mostly just kept around to show how the project evolved over time: neo4j_to_pyvis_example.ipynb, neo4j_to_pyvis_example.ipynb




# Pokemon_Cluster_analysis

## 1.Introduction
In this Notebook, we will analyze which Pokemon are the strongest and weakest based only on the type the Pokemon has been assigned. Using K-Means clustering we will also be clustering which Pokemon are alike based on the Pokemon type combinations. We will also be exploring several different methods to find the optimal number of clusters This will allow the user to organize their starting Pokemon so that the trainer will have a strong attack and defence no matter what Pokemon the opponent plays.


## 2. What is a Pokemon?
Pokemon are creatures in a video game that are used to battle against other Pokemon. A person who owns Pokemon for battle is called a trainer, typically trainers duel each other in a Pokemon battle with a set of 6 Pokemon each. Pokemon are assigned types along with different attacks, each attack is also assigned a type. This is important because each Pokemon type is assigned strenths and weaknesses. For example, Charmander is a fire type Pokemon and because he is fire type he is weak if he is attacked by a water move and thus will deal extra damage to Charmander if attacked. Charmander also has a set of attacks, of course he will be assigned fire attacks but he might have an array of other attack types too. His fire attacks will be strong against grass type Pokemon and deal extra damage against grass type Pokemon. One last thing, Pokemon have be assigned up to two types. For example, Charazard is both fire and flying type, this comes with both weakness and advantages. Along with the characteristics of fire type moves that we discussed Charazard also adops the strenths and weaknesses of flying type Pokemon. Fo example, Charazard will be strong against fighting type Pokemon along with grass types and weak against electricc types along with water.


## 3. The Data
The data set used in this notebook was obtained in Kaggle and contains the weakness muliplier for about 500 Pokemon for each type of attack it encouners. If the attack is super affective on the Pokemon it will be assigned a 2. If is weak or super weak it will be assigned a .5 or .25. If it is upaffected at all it will be assigned 0. Lastly, if the attack has no special affect it will be assigned a 1.

# kNearestNeighbours
In this tutorial, I describe the k-Nearest Neighbors (kNN) algorithm, a simple non-parametric supervised learning method for classification and regression.

Here is a simple analogy. Assume you are in Johannesburg for the first time and you have a sudden craving for the best lamb shank around. You don't know Jo'burg well, so you decide to rely on local wisdom (bo-Godfather soh!) - kind of like how kNN works.

(a) You find a few locals (that's your $k$ in kNN): You spot five friendly Jo'burg locals nearby and decide they will be your go-to 'neighbours' for recommendations.

(b) Ask for their lamb shank picks: You ask each person where to find the best lamb shank. Three of them point you to a famous spot in Maboneng (kidding!), while the others suggest different places like Rosebank or Sandton.

(c) Follow the majority: Since three out of five locals recommend the same place, you decide to trust their judgment and head there, assuming the lamb shank must be exceptional if most of the locals are raving about it.

Simple ne? This type of kNN is used for classification. 

Now for regression, it will work like this. Let's say you're in Johannesburg again, but this time you're not just looking for the best lamb shank—you want to find out how much it typically costs around town.

(a) Find some locals to ask (k):  You choose five locals nearby, as they seem familiar with the restaurant scene.

(b) Ask each local for their price estimate: You ask each of them how much they'd expect to pay for a lamb shank at a good restaurant nearby. One says around 120 Rand, another says 130 Rand, and so on.

(c) Average the answers: You take the average of their five estimates to get a more balanced view. If the locals suggest prices like 120, 130, 110, 125, and 115 Rand, you'd calculate the average to estimate the likely price, which in this case would be around 120 Rand.

Simple ne? This type of kNN is used for regression.

In the Jupyter notebook, I have implemented the kNN from scratch with numerical examples.

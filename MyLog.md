<h1>100 Days Of Code with Neelabh Singh</h1>

<img src="https://cdn.pixabay.com/photo/2015/01/08/18/24/programming-593312_960_720.jpg" alt="Image of coder" width="320px" height="213px">

Hi everyone! I am about to embark on a heroic adventure that will involve 100 days of coding. The rules are simple - code for an hour everyday and tweet/git about it with #100daysofcode. 

I plan to build epic android apps, polish my programming skills till they start shining like a diamond, and become an Android wizard with powers rivaling that of Gandalf and Albus Dumbledore. :)     

Some moments, I will feel like the smartest man alive. Others moments, I will feel like a stupid idiot. But each day, I will be a valiant warrior, fighting to improve my Android development skills('Or Die Tryin'). - Line by MightyJoe (can't come up with a better one)
 
Say cheers to **#100DaysofCode with _Neelabh Singh_**.

<img src="https://avatars2.githubusercontent.com/u/16917821?s=460&v=4" alt="Headshot of Neelabh Singh" width="150px" height="150px">

<p><b>Follow me on Twitter </b><a href="http://www.twitter.com/neelabh2006">here</a>.</p>

<p><b>Check out my repos </b><a href="https://github.com/Mightysigma-s">here</a>.</p>
<hr>
<br>
<h2>Day 1: Thursday January 3, 2019</h2>
<p><b>Today's Progress:</b> I've been working on a baking app and today I tried integrating the card view inside recycler view to show a list of recipes. I also used the ButterKnife library for binding to make the code less verbose.</p>
<p><b>Thoughts:</b> I had to look at a tutorial to refresh my concepts regarding RecyclerView and CardView as I am a bit rusty currently. But I plan to take this project to a professional level and am looking to integrate both text and images in the CardView. Currently, I am getting an view inflater error in my CustomAdapter class which I need to figure out.</p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/Baking%20App%20Wireframe.jpg" alt="Baking App Wireframe" width="900px">
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Day1.JPG" alt="Error Day 1">
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1080864411630403584">NeelabhS Day 1</a></p> 

<h2>Day 2: Friday January 4, 2019</h2>
<p><b>Today's Progress:</b> I made further progress with the baking app. I resolved the layout inflation error which I mentioned on Day 1. I also ran the CardView inside RecyclerView for which I have attached a screenshot below.</p>
<p><b>Thoughts:</b> The layout inflation error was caused by using android:support.v7.widget.CardView instead of android.support.v7.widget.CardView. Silly me! Hard to believe that such a minor error took around 1 hour to figure out. Also, I realized I shouldn't use match_parent in CardView height else it taken up the entire space and doesn't display other items in the list. I am liking this habit of logging as it helps me in noting down the error so that I do not commit them again. If I commit them gain I just have to look at the solution recorded here. :)</p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Day2.png" alt="CardView with RecyclerView Day 2" width="150px">
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1081117585675075584">NeelabhS Day 2</a></p>

<h2>Day 3: Saturday January 5, 2019</h2>
<p><b>Today's Progress:</b> After completing the frontend for the Main Recipes screen, I started work on the Recipe Instructions layout that would show up when a particular recipe is clicked. I plan to use RecyclerView for the same. Another important decision was to take the approach of first completing the front-end for all layouts and then work on the backend.</p>
<p><b>Thoughts:</b> Had some confusion regarding the naming of layout files which are of two types. The main recyclerview and the supporting detailed layout for each element in recyclerview. Decided on using the name as combination of main-function-performed_main and _layout for the two files. Example, recipe_main and recipe_layout. Also, currently figuring out the best way to integrate onClick in recyclerview between main activity class and adapter class.</p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/Recipe%20Instructions.JPG" alt="100DaysofCode Day 3 Recipe Instructions View" width="150px">
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1081460336165830656">NeelabhS Day 3</a></p>

<h2>Day 4: Monday January 7, 2019</h2>
<p><b>Today's Progress:</b> The Recipe Instructions layout has been added using RecyclerView. An image has been added for the same.</p>
<p><b>Thoughts:</b> The incorporation of onClick element in RecyclerView is a bit tricky. Right now I have added the onClick element in the MyViewHolder constructor. However, to do that I had to make context filed static which is not the best practice and results in a memory leak. Need to find a better way to do it. Also, more formatting is needed to make the second screen look appealing.</p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/Baking%20App%203.png" alt="100DaysofCode Day 4 Recipe Instructions Layout" width="150px">
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1082277603900309504">NeelabhS Day 4</a></p>

<h2>Day 5: Tuesday January 8, 2019</h2>
<p><b>Today's Progress:</b> Modified the static name/images in the Recipe list view to make it look more like a baking app. Added ingredients view to recipe steps layout.</p>
<p><b>Thoughts:</b> Figuring out how to make the RecylerView of recipe steps look pretty by using ItemDecoration, Dividers and Spaces. Also, thinking on how to add a bulleted list of ingredients from a string array to the ingredients view in recipe steps layout.</p>
<p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/bakingappday5-1.png" alt="100DaysofCode Day 5 Recipe List Layout" width="150px"/> 
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/bakingappday5-2.png" alt="100DaysofCode Day 5 Recipe Steps Layout with Ingredients" width="150px"/>
</p>
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1082580155627909121">NeelabhS Day 5</a></p>

<h2>Day 6: Wednesday January 9, 2019</h2>
<p><b>Today's Progress:</b> Added lines between the steps in the RecyclerView. Though about how to add ingredients as bullets or listview.</p>
<p><b>Thoughts:</b> Adding lines between items in recyclerview is quite simple uisng dividerdecoration. Took time as I realized I was adding it a wrong activity. Silly me!</p>
<p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/bakingappday6.png" alt="100DaysofCode Day 6 Recipe List Lines" width="150px"/> 
</p>
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1083001243520380928">NeelabhS Day 6</a></p>

<h2>Day 7: Thursday January 10, 2019</h2>
<p><b>Today's Progress:</b> Added ingredients in the form of a bullet in the recipe steps layout. Also, explored ViewPager for creating swipeable receipe steps pages.
<p><b>Thoughts:</b> Android Studio hangs in case the pending update is not made. Looks like an evil plan by these guys to make sure user keeps updating the platform asap! Also, I would be exploring exoplayer, tabview, and viewpager in the coming layout so quite excited. Note to myself, always code with 100% concentration. Debugging wastes a lot of time for simple activities. </p>
<p>
<img src="https://github.com/sigma-s/100-Days-of-Code/blob/master/Images/bakingappday7.png" alt="100DaysofCode Day 7 Recipe Ingredients List" width="150px"/> 
</p>
<p><b>Link to Tweet:</b> <a href="https://twitter.com/neelabh2006/status/1083378312884432896">NeelabhS Day 7</a></p>


# kotrreviews.github.io
 A gaming review website.




1. Create a new file in the reviews folder
2. Create a new folder in the review-images folder and add imgages
2. Update home tiles to include new article
3. Update reviews tiles to include new article

1.1. Copy all of the code in the party-hard-go.html file located in the reviews folder.
1.2. Right-click the reviews folder > New File > enter example-name and add ".html" at the end (E.G. example-name.html).
1.2. Paste all of the code from party-hard-go.html into example-name.html and replace all necessary article info.
1.3. Ctrl + S to save your file.

2.1. In the Reviews folder, right-click review-images > New Folder (use Kebabcase for names longer than one word. E.G. more-than-one-word)
2.2. Drag and drop article images

3.1. In the root folder, open index.html and locate
"<!--reviews container-->".
3.2. Select the tile you would like to replace with the new article and replace all necessary article info (Tiles are placed in order from left to right).

4.1. In the root folder, open opinion.html and locate
"<!--container-->".
4.1 Between "<div class="about-container">" and
<div class="tile-container"> copy and pase this code:

<div class="tile-container">
              <div class="img-container">
                <a href="./reviews/monopoly-mobile.html">
                <img  src="reviews/review-images/monopoly/1.png" alt="screenshot">
                </a>
              </div>
              <a class="info-container" href="./reviews/monopoly-mobile.html">
                <p class="genre">Strategy</p>
                <div class="text-hover-opacity">
                <h3>Monopoly</h3>
                <p class="text-preview">Why would you buy Monopoly for your mobile device when you could purchase a perfectly reasonable version of the board game at your nearby Target/Walmart?...</p>
                </div>
                <p class="read-time">Dec 15 ∙ 2 min</p>
              </a>
          </div>

4.2 Update all necessary article info.

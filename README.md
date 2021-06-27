# Codefest_enigma
Enigma Data Science Competition organized by Dept of Computer Science, IIT BHU as a part of Codefest'19.

I, in a team of 2, got first prize among first/second years and securing an overall rank of 18 among 500+ teams, which included industry professionals as well.

## Approach

### DATA

Train.csv- this had research papers with several attributes and their citation counts.

Author.csv- Each research paper had several authors and various attributes about these were given in this.

Test.csv- we had to predict citation counts for research papers with given attributes.

### FEATURE EMGINEERING

For a particular research paper, used author data to gather top 3 common interest fields, and then merged that with train data.

### MODEL

Used embedding layer to convert top 3 topics to embedded vector. Then we applied a simple neural model with activation function selu.

.


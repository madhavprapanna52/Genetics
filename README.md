# CRUNCH 1 : PREDICTING EFFECT OF HELD OUT SINGLE GENE PERTURBATION
How to predict single cell trancriptomic response to single gene perturbationthat were not measured in testing

How Entire gene profile would look after removing one single non experimented gene.

After we remove a gene how other gene would be expressed which means
Every gene have their quantity based outcome of how much they are being shown in cell,  as we remove gene what happens to other genes effect in the cell

output required : Generate fake single cell data, Expression value for single selected gene, also predict the cell state adipo, preadipo and lipo

Approach outline
    1. Using GAN for making synthetic data for the cell,
    Complexity analysis and learning and result in good synthetic output
    2. Classification models for making the final ratio output for the final predictions of the synthetics output

## Basic journey sketch
1. Train GAN model for generating synthetic data set for final output
2. Making simple classification model for final ratio generation based on some algorithmic classification also for less ML load
3. Submit the results out for the final predictions

## Future Goals
+ Make own pattern prediction model which is tailoired for the specifically genetic mutations
+ Algorithmic and nural fusion model for prediction outputs
+ Improving upon the base models for tunning hyper parameters


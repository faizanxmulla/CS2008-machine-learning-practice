## Data preprocessing Techniques

___
**Data preprocessing** involves several transformations that are applied to the raw data to make it more amenable for learning. It is carried out before using it for model training or prediction.

There are many pre-processing techniques which include : 
* **Data Cleaning**
    * Data Imputation

    * Feature Scaling

* **Feature transformation**
    * Polynomial Features

    * Discretization

    * Handling categorical features

    * Custom Transformers

    * Composite Transformers

        * Apply Transformation to diverse features

        * TargetTranformedRegressor

* **Feature selection**
    * Filter based feature selection

    * Wrapper based feature selection

* **Feature Extraction**
    * DictVectorizer
    
    * Principal Component Analysis(PCA)

The transformation are applied in a specific order and the order can be specified via `Pipeline`.

We need to apply different transformations based on the feature type. `FeatureUnion` helps us perform that task and combine outputs from multiple transformations into a single transformed feature matrix.

We will also study as how to visualize this pipeline.



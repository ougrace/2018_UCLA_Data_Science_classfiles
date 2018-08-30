1. Case Study - The Seeds Data Set
   1. Introduction
      1. Structure of the Case Study
      1. 
      1. Programming Methods
      1. Discussions
   1. Load and Verify Data
      1. Load the Seeds Data Set from a URL
         1. Load the Python Numerical Stack
         1. Run the IPython Magic Command `%matplotlib inline`
         1. Programming Method: Import Entire Libraries Versus Specific Classes or Modules
         1. Define the Data Set URL
         1. Display a sample of the Data Set URL
         1. Use `pd.read_csv()` to Load Data as `DataFrame`
         1. Manually Define Column Names
         1. Basic Data Verification
      1. Verify Type Casting
         1. Display `DataFrame.dtypes`
         1. Display Unique Values for the `seed_class` Column
         1. Programming Method: Transform and Reassign a Variable
      1. Fix Typecasting Error
         1. Cast `seed_class` as a Pandas Column of type `category`
         1. Display `DataFrame.dtypes`
      1. Save Data Set as Local Files
         1. Programming Method: The Python Pickle Format
   1. Exploratory Data Analysis
      1. Basic EDA
         1. Programming Method: Working in Multiple Notebooks
         1. Load the Python Numerical Stack
         1. Load Saved Data Set
         1. Visualization: Prepare a Pair Plot
         1. Discussion: Interpretation of the `PairGrid` Visualization
      1. Linear Regression on Features to Study Correlation
         1.
      1. Single Variable Logistic Regression for Inferring Feature Importance
         1. Import the `LogisticRegression` Class and instantiate a `LogisticRegression` Model
         1. Programming Method: `for`-loop Over Features
         1. Programming Method: Manually Build a `DataFrame`
         1. Discussion: Interpreting Coefficients of Single Variable Logistic Regression
      1. T-SNE Model for Visualization of High-Dimensional Data
         1. Create `features` and `target` Subsets of Data Set
         1. Import the `TSNE` Class
         1. Programming Method: Classes and Objects
         1. Instantiate a `TSNE` Model
         1. Fit the Model and Transform the Data
         1. Programming Method: Fit and Transform
         1. Discussion: Two-Dimensional Representation of our Data Set
      1. Visualization: Scatter Plot by Class
         1. Programming Method: Import Functions From File
         1. Import `scatter_plot_by_class`
         1. Programming Method: A Simple Method for Controlling Plots
         1. Discussion: Two-Dimensional Scatter Plot by Class
      1. K Means Cluster Model for Examining Class Seperation
         1. Import the `KMeans` Class
         1. Instantiate a `KMeans` Model
         1. Fit the Model
         1. Access Cluster Labels from the Fit Model
         1. Visualization: Scatter Plots by Class and Cluster
         1. Discussion: Scatter Plots by Class and Cluster
      1. Multiple Variable Logisitic Regression and K Nearest Neighbors Classifier for Examining Class Separation
         1. Import `scatter_plot_with_decision_boundary`
         1. Import the `KNeighbors Classifier` Class
         1. Instantiate a `KNeighbors` Model
         1. Visualization: Scatter Plot By Class with Model-Based Decision Boundary
         1. Discussion: Scatter Plot By Class with Model-Based Decision Boundary 
   1. Appendix: `visualization.py`
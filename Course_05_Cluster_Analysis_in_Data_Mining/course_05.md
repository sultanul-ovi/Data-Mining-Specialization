# Cluster Analysis in Data Mining

Discover the basic concepts of cluster analysis, and then study a set of typical clustering methodologies, algorithms, and applications. This includes partitioning methods such as k-means, hierarchical methods such as BIRCH, and density-based methods such as DBSCAN/OPTICS. Moreover, learn methods for clustering validation and evaluation of clustering quality. Finally, see examples of cluster analysis in applications.

# Cluster Analysis Syllabus

## Course Description

This course covers the concepts and methodologies for cluster analysis, also known as clustering, data segmentation, or unsupervised learning. Cluster analysis is a crucial subfield of data mining. Topics include:

- Basic concepts of cluster analysis
- Partitioning methods (e.g., k-means)
- Hierarchical methods (e.g., BIRCH)
- Density-based methods (e.g., DBSCAN)
- Grid-based methods (e.g., CLIQUE)
- Clustering validation

Students will also work with clustering software and complete programming assignments.

## Course Goals and Objectives

By the end of this course, students will be able to:

- Recall basic concepts, methods, and applications of cluster analysis.
- Learn various distance and similarity measures (e.g., Euclidean, Cosine similarity, correlation measures).
- Understand and apply partitioning algorithms (e.g., K-Means, K-Medoids).
- Explore hierarchical clustering methods (e.g., BIRCH, CURE, CHAMELEON).
- Implement density-based clustering algorithms (e.g., DBSCAN, OPTICS).
- Apply grid-based clustering methods (e.g., STING, CLIQUE).
- Evaluate clustering results using internal and external validation measures.

## Textbook and Readings

While lectures are designed to be self-contained, the following textbook is recommended:

- Han, J., Kamber, M., & Pei, J. (2011). **Data Mining: Concepts and Techniques (3rd ed.)**. Morgan Kaufmann.

Optional PDF readings from the book (Chapters 2, 10, 11, and 13) are available for free.

## Course Outline

The course is divided into 4 weekly modules with 6 lessons. Suggested readings from the textbook are optional.

### Week 1 (Lessons 1-2)

- **Topics**: Introduction to Cluster Analysis, Similarity Measures
- **Suggested Reading**: Chapter 2, Chapter 10

### Week 2 (Lessons 3-4, Part 1)

- **Topics**: Partitioning-Based Clustering Methods, Hierarchical Clustering Methods (Part I)
- **Suggested Reading**: Chapter 10

### Week 3 (Lesson 4, Part 2 - Lesson 5)

- **Topics**: Hierarchical Clustering Methods (Part II), Density-Based and Grid-Based Clustering Methods
- **Suggested Reading**: Chapter 10

### Week 4 (Lesson 6)

- **Topic**: Cluster Validation
- **Suggested Reading**: Chapter 10



# Lesson 1 Overview: Cluster Analysis - An Introduction

## Objectives

In this lesson, you will explore the key concepts and applications of **cluster analysis**, a fundamental method in **unsupervised learning**. You will:

- Understand the purpose and importance of **cluster analysis** in various applications, including data segmentation.
- Learn about the basic concepts, requirements, and challenges of cluster analysis, as well as its multi-dimensional categorization.
- Explore different clustering methodologies, such as **distance-based**, **density-based**, **grid-based**, and **probabilistic clustering** methods, and understand how data types impact these approaches.
- Recognize the role of **dimensionality reduction** techniques like **spectral clustering** and **non-negative matrix factorization** in clustering.
- Understand how user insights and constraints (e.g., **semi-supervised** or **user-guided clustering**) influence the choice of clustering methods and their results.

Key concepts include **similarity measures**, **distance measures**, **high-dimensional clustering**, and **constraint-based clustering**, which will help you understand the wide range of techniques and challenges in cluster analysis.

## Guiding Questions

As you work through the lesson, develop your answers to the following questions:

- What is cluster analysis, and why is it considered unsupervised learning?
- What are the potential applications of cluster analysis?
- Under what conditions is clustering an independent task, and when is it part of the overall data analysis process?
- What are the key factors and challenges in cluster analysis?
- What are the typical clustering methodologies and methods for different types of data?
- How do user insights affect clustering?


# Lesson 2 Overview: Similarity Measures for Cluster Analysis

## Objectives

In this lesson, you will learn how to compute **similarity** and **distance measures** for various types of data, including numeric, binary, categorical, and mixed data types. The key objectives include:

- Understanding the basic concepts and importance of **similarity measures**.
- Applying different distance formulas such as **Euclidean**, **Manhattan**, and **Supremum** distances for numeric data.
- Using proximity measures for **symmetric** and **asymmetric binary variables**, including the **Jaccard coefficient**.
- Computing distance measures for **categorical**, **ordinal**, and **mixed attributes**.
- Calculating proximity between vectors using **cosine similarity**.
- Understanding and computing correlation measures like **covariance** and the **correlation coefficient** to evaluate the relationship between variables.

Key terms such as **Minkowski distance**, **cosine similarity**, **proximity**, and **correlation** will be emphasized throughout the lesson to help you grasp the methods for evaluating similarity and distance in different data contexts.


## Guiding Questions

- Why is it important to use different measures for computing similarity between objects?
- Why is Minkowski distance a general measure of distance on numeric data? When should we use Euclidean, Manhattan, or Supremum distance?
- When should proximity measures be chosen for symmetric vs. asymmetric binary variables?
- How do we compute distance between categorical, ordinal, and mixed attributes?
- What is the best proximity measure between two vectors?
- How do we compute correlation measures between two variables? What are the differences between covariance and correlation coefficient?




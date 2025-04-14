observations:
1. LDA consistently performs best for all models. Indicates that LDA captures class-discriminative features very effectively.
    

2. PCA shows varied performance
Random Forest performs better on PCA (0.933333) than on Original (0.888889). But Logistic Regression degrades under PCA (0.888889).
PCA is unsupervised → it maximizes variance, not class separability → may not help models that rely heavily on class boundaries.

3. Original feature space leads to moderate performance
Models perform fairly well but not best.
Suggests raw features have signal, but dimensionality reduction helps focus the learning process.

4. Decision Tree is robust across techniques
Same score for PCA and Original (0.911111).
Slightly lower than LDA but stable → indicates less sensitivity to transformed features compared to other models.


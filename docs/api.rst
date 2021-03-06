API reference
=============

:mod:`creme.base`: Base classes
-------------------------------

.. automodule:: creme.base
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :template: class.rst
   :nosignatures:

   base.BinaryClassifier
   base.Clusterer
   base.MultiClassifier
   base.Regressor
   base.Transformer


:mod:`creme.cluster`: Clustering
--------------------------------

.. automodule:: creme.cluster
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   cluster.KMeans


:mod:`creme.compat`: Compatibility utilities
--------------------------------------------

.. automodule:: creme.compat
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :template: class.rst
   :nosignatures:

   compat.SKLClassifierWrapper
   compat.SKLClustererWrapper
   compat.SKLTransformerWrapper
   compat.SKLRegressorWrapper


:mod:`creme.compose`: Model composition
---------------------------------------

.. automodule:: creme.compose
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   compose.Pipeline
   compose.StandardScaleRegressor
   compose.TransformerUnion


:mod:`creme.ensemble`: Ensemble models
--------------------------------------

.. automodule:: creme.ensemble
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   ensemble.BaggingClassifier
   ensemble.HedgeClassifier


:mod:`creme.feature_extraction`: Feature extraction
---------------------------------------------------

.. automodule:: creme.feature_extraction
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   feature_extraction.CountVectorizer
   feature_extraction.GroupBy
   feature_extraction.TargetEncoder
   feature_extraction.TFIDFVectorizer


:mod:`creme.feature_selection`: Feature selection
-------------------------------------------------

.. automodule:: creme.feature_selection
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   feature_selection.RandomDiscarder


:mod:`creme.linear_model`: Linear models
----------------------------------------

.. automodule:: creme.linear_model
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   linear_model.LinearRegression
   linear_model.LogisticRegression
   linear_model.PassiveAggressiveClassifier
   linear_model.PassiveAggressiveRegressor
   linear_model.PassiveAggressiveIClassifier
   linear_model.PassiveAggressiveIRegressor
   linear_model.PassiveAggressiveIIClassifier
   linear_model.PassiveAggressiveIIRegressor


:mod:`creme.model_selection`: Model selection
---------------------------------------------

.. automodule:: creme.model_selection
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   model_selection.online_score


:mod:`creme.multiclass`: Multi-class classification
---------------------------------------------------

.. automodule:: creme.multiclass
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   multiclass.OneVsRestClassifier


:mod:`creme.naive_bayes`: Naive Bayes models
--------------------------------------------

.. automodule:: creme.naive_bayes
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   naive_bayes.MultinomialNB


:mod:`creme.optim`: Optimization
--------------------------------

.. automodule:: creme.optim
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

Optimizers
++++++++++

.. autosummary::
   :toctree: generated/
   :nosignatures:

   optim.AdaDelta
   optim.AdaGrad
   optim.Adam
   optim.FTRLProximal
   optim.Momentum
   optim.NesterovMomentum
   optim.RMSProp
   optim.VanillaSGD


Learning rate schedulers
++++++++++++++++++++++++

.. autosummary::
   :toctree: generated/
   :nosignatures:

   optim.ConstantLR
   optim.LinearDecreaseLR


Loss functions
++++++++++++++

.. autosummary::
   :toctree: generated/
   :nosignatures:

   optim.EpsilonInsensitiveHingeLoss
   optim.LogLoss
   optim.HingeLoss
   optim.AbsoluteLoss
   optim.SquaredLoss


:mod:`creme.preprocessing`: Preprocessing
-----------------------------------------

.. automodule:: creme.preprocessing
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   preprocessing.FeatureHasher
   preprocessing.OneHotEncoder
   preprocessing.StandardScaler
   preprocessing.MinMaxScaler


:mod:`creme.reco`: Recommendation algorithms
--------------------------------------------

.. automodule:: creme.reco
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   reco.RandomNormal
   reco.SGDBaseline


:mod:`creme.stats`: Running statistics
--------------------------------------

.. automodule:: creme.stats
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   stats.Count
   stats.Kurtosis
   stats.Mean
   stats.Min
   stats.Max
   stats.NUnique
   stats.PeakToPeak
   stats.Skew
   stats.Sum
   stats.Variance

:mod:`creme.stream`: Streaming utilities
----------------------------------------

.. automodule:: creme.stream
   :no-members:
   :no-inherited-members:

.. currentmodule:: creme

.. autosummary::
   :toctree: generated/
   :nosignatures:

   stream.iter_numpy
   stream.iter_sklearn_dataset
   stream.iter_pandas

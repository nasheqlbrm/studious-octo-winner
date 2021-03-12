[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nasheqlbrm/studious-octo-winner/HEAD?urlpath=%2Fvoila%2Frender%2Fks-3.0-flag-classification-ui.ipynb)

# US State/Territory Flags Classifier

Following the first three lessons of the MOOC *Practical Deep Learning for Coders* (from https://course.fast.ai/) we create the following notebooks.

* ks-1.0-flag-classification-train.ipynb
	* Images of flags are downloaded from the Duck Duck Go search engine for use in model training and validation.
	* Transfer learning is used to train a classifier that can distinguish between images of flags for the different states and territories in the United States.
	* The trained classifier is serialized into a .pkl file so that it can be used for inference.
* ks-3.0-flag-classification-ui.ipynb
	* A web application is created where the image of a flag can be uploaded and the application returns 1) the flag's US State and/or Territory and 2) the model's confidence in the classification.

Finally the result web application is hosted using Binder (see link at the top of this README).
	
![MLU-Explain Logo & Title](./assets/readme_header.png)

This repository holds the code used for Amazon's **MLU-Explain** educational articles on machine learning.  MLU-Explain exists to illustrate core machine learning concepts using visual essays in a fun, informative, and accessible manner.

This material exists as supplementary educational material for [Machine Learning University (MLU)](https://aws.amazon.com/machine-learning/mlu/), which provides anybody, anywhere, at any time access to the same machine learning courses used to train Amazon’s own developers on machine learning.


# Articles

Currently, there are **1** articles published:

### Bias Variance Tradeoff
<img src="./assets/bias-variance.png" alt="Bias Variance Tradeoff Article Image" width="400"/>

**Title**: The Bias Variance Tradeoff

**Summary**: Understand the tradeoff between under- and over-fitting models, how it relates to bias and variance, and explore interactive examples related to LASSO and KNN.

**Code**:

**Authors**: Jared Wilber, Brent Werness



## Running Locally

This article holds code for each articles, as well as the generated builds from the code (e.g. the static assets comprising the articles).

First, clone this repo.

```bash
git clone https://github.com/aws-samples/aws-mlu-explain.git
```

Next, cd into the article of interest and install the required libraries.

```bash
# e.g. bias variance tradeoff article
cd bias-variance
# install libraries
npm install
```

Now, to run the development version:
```bash
npm start
```

To build and view the static assests:
```bash
# build assets
npm run build
# view generated article
cd dist/
# run local server
python3 -m http.server # or just `live-server`
```

Running the articles locally requires 
## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.


# ConstraintsFromTemplates [![Build Status](https://travis-ci.org/WikidataQuality/ConstraintsFromTemplates.svg?branch=master)](https://travis-ci.org/WikidataQuality/ConstraintsFromTemplates) [![Coverage Status](https://coveralls.io/repos/WikidataQuality/ConstraintsFromTemplates/badge.svg)](https://coveralls.io/r/WikidataQuality/ConstraintsFromTemplates) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/WikidataQuality/ConstraintsFromTemplates/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/WikidataQuality/ConstraintsFromTemplates/?branch=master)
Parses the property talk pages of Wikidata to extract the constraints and initially fill the constraints table for the WikidataQualityConstraints extension.

## Installation
```
git clone https://github.com/WikidataQuality/ConstraintsFromTemplates.git
cd ConstraintsFromTemplates
pip install -r requirements.txt
```

## Usage
`python csvScriptBuilder.py`

### Running the tests
```
py.test
```

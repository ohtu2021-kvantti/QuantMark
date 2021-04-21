# Testing

Test are conducted with pytest. 

### Unit tests:
- `$ python manage.py test` (runs unit tests)

## What was tested

```
📦tests
 ┣ 📜testAlgorithmDetails.py
 ┣ 📜testCompareAlgorithms.py
 ┣ 📜testHomepage.py
 ┣ 📜testLogin.py
 ┣ 📜testMyAlgorithms.py
 ┣ 📜testNewAlgorithmType.py
 ┣ 📜testNewMolecule.py
 ┣ 📜testNewVersion.py
 ┗ 📜testUpdateAlgorithm.py
```

 Test are written corresponding the individual views of the web application.
 
 Most of the test names are self explanatory. Some methods are rather long because testing certain elements require initializing multiple different objects.

 ## Reasons for testing
 Since the application involves several intertwined objects and analyzing benchmark results on a separate backend, testing each "nook and cranny" makes it easier to ensure that inputs and outputs are valid, tasks get executed and so on.

 ## What is not tested
 The UI-functionality is not tested, but during the development Google Lighthouse reports have been generated and changes have been made accordingly. Challenges with f.ex. bad layout have been "tested" in this way.

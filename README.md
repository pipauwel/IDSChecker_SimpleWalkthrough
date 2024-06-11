# IDSChecker Simple Walkthrough
This is a repository that includes a simple walkthrough of creating a sample IDS document (Information Delivery Specification), and validating an IFC file with that IDS document. This is entirely inspired and taken from:
- https://github.com/buildingSMART/IDS/tree/development/Documentation
- https://github.com/IfcOpenShell/IfcOpenShell/tree/v0.8.0/src/ifctester

The walkthrough is available as a Python notebook, and you can find this in `ifctester.ipynb`. The repository also includes:
- a sample IFC file: `smallhouse.ifc`
- an example output IDS XML file: `SampleIDS.xml`
- an example output HTML file: `report.html`

There are a number of ways in which you can use the Python notebook and create the above outputs (IDSXML, HTML), but the easiest option is to use Google Colab. To do this, take the following steps:

1. Go to https://colab.research.google.com/github/pipauwel/IDSChecker_SimpleWalkthrough/blob/main/ifctester.ipynb
2. In the menu of Google Colab, add the `smallhouse.ifc` file
3. You can now execute the code from top to bottom and create and validate your own IDS files.

Good luck - any questions, ask in the Q&A sessions!

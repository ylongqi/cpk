# Creative Procedural-Knowledge Extraction (CPK)

Each line of the **dataset.json** file contains a JSON object that encodes annotations for a design tutorial. The JSON object contains following keys:

* **text:** *string*, raw text from a web design tutorial.
* **title:** *string*, the title of the tutorial.
* **goal_sentence:** *string*, the original sentences describing the design goal.
* **goal_summary:** *string*, summary of the design goal.
* **annotations:** *list*, a list of action (command, usage) annotations.
  * **command:** *string*, the command used.
  * **sentence:** *string*, the original sentences describing the usage of the command.
  * **start:** *integer*, the starting index of the above **sentence** in the **text**.
  * **end:** *integer*, the ending index of the above **sentence** in the **text**.
  * **summary:** *string*, summary of the command usage.
  

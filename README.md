# Comparing Refactoring Mechanics (Artifacts)

# Evaluation

## Experimental Setup
	* Fedora 33 (Linux)
	* Java Virtual Machines:
	  * Oracle 1.8 or OpenJDK 1.8
	* [Eclipse IDE 4.16](https://www.eclipse.org/downloads/packages/release/2020-06/r)

## Refactoring Detection Tools
	* [RefactoringMiner 2.0.3](https://github.com/tsantalis/RefactoringMiner/commit/fee2968)
	* [RefDiff 2.0](https://github.com/aserg-ufmg/RefDiff/commit/2a06cfd)

## Algorithm
	* [Extract Method pseudocode](https://github.com/osmarleandro/comparing-mechanics/blob/main/algorithm/extract-method-pseudocode.pdf)

## Subjects
	* [Input Programs](https://github.com/osmarleandro/comparing-mechanics/blob/main/subjects/subjects.csv)
	* [GitHub Gradle Projects](https://github.com/osmarleandro/comparing-mechanics/blob/main/subjects/repositories-github-gradle-projects.json)

# Results

## Transformations
	* [Extract Interface](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/ExtractInterface.csv)
	* [Extract Method](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/ExtractMethod.csv)
	* [Inline Method](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/InlineMethod.csv)
	* [Move Method](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/MoveMethod.csv)
	* [Pull Up Method](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/PullUpMethod.csv)
	* [Push Down Method](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/PushDownMethod.csv)
	* [Rename Class](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/RenameClass.csv)
	* [Rename Method](https://github.com/osmarleandro/comparing-mechanics/blob/main/results/RenameMethod.csv)

## Bug Report
	* [Issues](https://github.com/osmarleandro/comparing-mechanics/blob/main/issues/issues.csv)
	* [Report Template](https://github.com/osmarleandro/comparing-mechanics/blob/main/issues/report-template.md)
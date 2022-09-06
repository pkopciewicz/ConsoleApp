# ConsoleApp
Dla Dataedo

For Dataedo

Changes made:

    File: Program.cs, error type: incorrect name of argument, added comment

    File: DataReader.cs, error type: problems with processing empty lines Solution: added condition which ignores empty lines

    //added empty line verification if (line!="") { importedLines.Add(line); }

    File: DataReader.cs, error type: incorrect condition, too much iterations Solution: replacing <= on < , added comment

    File: DataReader.cs, error type: problems with NULL values which are at 0 index of list Solution: skipping 0 index of list

    foreach (var importedObject in ImportedObjects.Skip(1))// added .Skip(1) function to prevent reading first element of // List which contains NULL values - accual List content starts with 1 index

5, 6, 7) File: DataReader.cs, error type: problems with NULL values which are at 0 index of list Solution: similar as at 4) but with shorter description in comment

In that form program is working. To deeper analise parts with assigning children and printing data I will have to get from You description with detailed purpose of Your program.

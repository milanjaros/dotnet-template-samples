The sample in this folder demonstrates:

 - PascalCasing a parameter value.
 - camelCasing a parameter value.
 - kebab-casing a paremeter value.
 - Regex replace a parameter value.
 - Chaining of value forms.

See

 - [`template.json`](./MyProject.Con/.template.config/template.json)
 - [`Program.cs`](./MyProject.Con/Program.cs)

Details

 - Value transformation is performed using `ValueForms`.
 - The sample uses `replace`, `titleCase`, `kebabCase`, `firstLowerCaseInvariant` and `chain` value forms.
 - More value forms can be found in [the source code](https://github.com/dotnet/templating/tree/main/src/Microsoft.TemplateEngine.Orchestrator.RunnableProjects/ValueForms).

Related
 - [Change String Casing](../11-change-string-casing/README.md)

[![Build status](https://ci.appveyor.com/api/projects/status/l5tsskn518iijvus?svg=true)](https://ci.appveyor.com/project/tatsuya/wpf-cheat-sheet)

# Best practices
* Use attribute syntax rather than property element syntax
  * For example, use \<Button Content="Content1" /> rather than \<Button>Content1\<Button/>
* Use {Binding Property1} rather than {Binding Path=Property1} as "Path=" is optional.
* Omit Grid.Row="0" and Grid.Column="0" as they are optional.
* Use ListView rather than ListBox because ListView inherits ListBox, which means ListView is better.

# Glossary
Name|Description
---|---
Binding source|Object
Binding target|GUI

# Links
* [Binding Sources Overview](https://docs.microsoft.com/en-us/dotnet/framework/wpf/data/binding-sources-overview)
* [Binding Mode Enum](https://docs.microsoft.com/en-us/dotnet/api/system.windows.data.bindingmode)

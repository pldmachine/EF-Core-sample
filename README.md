# EntityFrameworkCore

## Migrations

**Note:** In order to work with EF tools for the command-line interfacse you have to install `Microsoft.EntityFrameworkCore.Tools.DotNet` package by editing the .csproj filel you can't use the install-package command or the package manager GUI.

```xml
<ItemGroup>
  <DotNetCliToolReference Include="Microsoft.EntityFrameworkCore.Tools.DotNet" Version="2.0.0" />
  <DotNetCliToolReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Tools" Version="2.0.0" />
</ItemGroup>
```

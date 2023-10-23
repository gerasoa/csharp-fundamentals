# Comprehensive C# Cheatsheet
<p align="center">
  <img src="images/csharp_1.png">
</p>

## Contents 

- Commands **[`dotnet new --list`](#Commands)**__,__**[`dotnet new console -n MyProject -f net6.0`](#Commands)**

- Types **[`Int`](#Int)**__,__ 
- Syntax 
- Linq


## Commands
`dotnet new --list` - Lists available templates to be run using dotnet new

`C:\>dotnet new sln -n MySolution`

```prompt
 Directory of C:\MySolution

23/10/2023  19:29    <DIR>          .
23/10/2023  19:27    <DIR>          ..
23/10/2023  19:29               441 MySolution.sln
               1 File(s)            441 bytes
               2 Dir(s)  48,576,237,568 bytes free
```





## String

## Boolean

## Double

## Int

```c#
string yourCodeOutput = "hello world"; // A saída do seu código

if (yourCodeOutput == "hello world")
{
    Console.WriteLine("Seu primeiro código imprime 'hello world'.");
}
else
{
    Console.WriteLine("Sua saída de código não é 'hello world'.");
}

```

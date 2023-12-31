<header>

<!--
  <<< Author notes: Course header >>>

-->

# CATEGORY

_File Extensions_
</header>

.txt Plain text files no formatting. e.g. headings, sub-headings, bold, italics, underlining, lists, etc.<br>
.md Markdown format does.

_Style Syntax_
</header>

Style	Syntax	Keyboard shortcut	Example	Output
**Bold**	** ** or __ __, Ctrl+B<br>
*Italic*	* * or _ _,Ctrl+I<br>
~~Strikethrough~~	~~ ~~<br>
**_Bold and nested italic_** ** ** and _ _<br>
***All bold and italic***	*** ***<br>
<sub>Subscript</sub>	<sub> </sub><br>
<sup>Superscript</sup>	<sup> </sup><br>

ALTCODES
|Symbol|Description|AltCodes|
|---|---|---|
|—|Em dash|Alt+0151|
|½|Half|Alt+0189|
|¼|Quarter|Alt+0188|
|¾|Fraction 3/4|Alt+0190|
|π|Pi|Alt+995|
|£|Pound|Alt+0163|
|·|Middle dot|Alt+250|
◁ △ ▽ ▷

C#
```csharp
// Correct examples. Avoid Hungarian notation or any other type identification in identifiers
int counter; //not icounter;
string name; //not strName;

// camelCase - only for parameter names
Local variables
Method arguments
Parameter e.g. public static int ToInt32(string value);
// _camelCase
Field name Private

// PascalCase - all identifiers/public member/type/namespace names with multiple words except parameter names. do not use underscore to differentiate words.
ClassName
Constructor
Enum value e.g. public enum FileMode { Append, ... }
Field name Public e.g. public class MessageQueue { public static readonly TimeSpan InfiniteTimeout; } public struct UInt32 {public const Min = 0; }
Interface
Method
Property
Namespace
Type

// Special case for 2 letters acronyms
IOStream
```


## REFERENCES
[C# Naming Conventions notes](https://github.com/ktaranov/naming-convention/blob/master/C%23%20Coding%20Standards%20and%20Naming%20Conventions.md)
[microsoft naming convention](https://learn.microsoft.com/en-us/dotnet/standard/design-guidelines/capitalization-conventions)

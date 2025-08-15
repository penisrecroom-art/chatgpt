# **Windows Il2Cpp Dumper**

A tool designed to dump il2cpp games in runtime using the il2cpp exports **(also works for games that have the export `il2cpp_domain_get_assemblies` protected)**.

If the module name of your targeted game is not GameAssembly.dll then you can change it in the il2cpp_dump.h file

## **Features**

- **Dumping of Constant Fields**  
  Extracts constant fields such as strings, booleans, and numeric types.

- **Numeric Field Extraction**  
  Dumps various numeric field types, including:
  - `int16`, `int32`, `uint16`, `float`, `double`, etc.

- **Supports Generic Types**  
  Includes the ability to dump:
  - `Dictionary<TKey, TValue>`
  - `List<T>`
  - `KeyValuePair<TKey, TValue>`
  - And more...

## **Credits**

- **Sxitxma** – Developer of the improved dumper.
- **Nullbit** – Contributor to the `GetProtectedExportName` function.
- **Perfare** – Original creator of the dumper.


## **Contact**

- Sxitxma - Discord: sxitxma (Sxitxma#1000)

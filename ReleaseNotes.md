# ![CakeBuild](https://github.com/cake-build/graphics/raw/master/png/cake-small.png) Cake.Incubator

### 1.0.15

- Added alias `MoveFile(FilePath source, FilePath destination)`
- Added alias `MoveFile(IEnumerable<FilePath> source, Directory destination)`
- Updated `ProjectParser(FilePath project, string configuration)` to cope with Project include wildcards  `<Content Include="app\**" />`

### 1.0.33

- Renamed package from Cake.Extensions ot Cake.Incubator
- Added .Dump(object) alias for outputting objects and collections to strings for logging
- Added optional message to .ThrowIfNullOrEmpty(obj, message)

### 1.0.34

- Adding strong typing environment variable alias `EnvironmentVariable<T>(name)` for parity with `Argument<T>`
- Adding `IEnumerable<T>.IsNullOrEmpty()` convenience extension

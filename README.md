# Batch Prokka Assemblies

Prokka批量执行脚本
Batch Prokka can help you execute prokka batch assemblies.

# Useage

You only need to specify two parameters, dataPath and outPath.

For example:

```
./batch-prokka-linux-amd64 -dataPath=/path/to/data -outPath=/path/to/out
```

The file name format example of the source file has been given in the [data directory](data).

Note: The folder cannot include any file other than the source file, such as. DS_ Store these invisible files.

# Cross platform

You can use this program directly on Linux, Windows and Mac, as long as your device has [Prokka](https://github.com/tseemann/prokka) installed.

[Windows](batch-prokka-windows-amd64)

[Mac](batch-prokka-mac-amd64)

[Linux](batch-prokka-linux-amd64)



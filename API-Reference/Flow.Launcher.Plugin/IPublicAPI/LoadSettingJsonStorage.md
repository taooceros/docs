# IPublicAPI.LoadSettingJsonStorage&lt;T&gt; method

Load JsonStorage for current plugin's setting. This is the method used to load settings from json in Flow. When the file is not exist, it will create a new instance for the specific type.

```csharp
public T LoadSettingJsonStorage<T>()
    where T : new()
```

| parameter | description |
| --- | --- |
| T | Type for deserialization |

## See Also

* interface [IPublicAPI](../IPublicAPI.md)
* namespace [Flow.Launcher.Plugin](../../Flow.Launcher.Plugin.md)

<!-- DO NOT EDIT: generated by xmldocmd for flow.launcher.plugin.dll -->

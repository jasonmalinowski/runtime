# System.Reflection.MetadataLoadContext
This provides a high-level API for inspecting types given raw assembly contents according to ECMA-335. The types from a provided assembly are loaded into a[`MetadataLoadContext`](https://learn.microsoft.com/dotnet/api/system.reflection.metadataloadcontext) instance which returns `System.Type`, `System.MemberInfo`, etc. However, these reflection types do not support invocation and they are different instances from the types returned from runtime introspection. Because of this, this allows any assembly to be read, even if it's for a different platform provided that all assembly references are accounted for.<br/>

This library takes a dependency on `System.Reflection.Metadata` for reading the assembly.

## Status: [Inactive](../system.reflection/overview.md#status)
The APIs and functionality are mature, but do get extended occasionally.

## Source

* [../System.Reflection.Metadata](../System.Reflection.Metadata)

## Deployment
[System.Reflection.MetadataLoadContext](https://www.nuget.org/packages/System.Reflection.MetadataLoadContext) NuGet package.

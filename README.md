# Validate.proto NuGet Package

This project provides a `validate.proto` file packaged as a NuGet package to enable validation support in C# projects. Since `envoy protoc-gen-validate` does not natively support C#, this package serves as a workaround to integrate validation rules into your C# applications.

## Installation

To install the NuGet package, run the following command in your NuGet Package Manager Console:

```sh
Install-Package EnvoyProtocValidate
```

Alternatively, you can add the package reference directly to your `.csproj` file:

```xml
<PackageReference Include="EnvoyProtocValidate" Version="1.0.0" />
```

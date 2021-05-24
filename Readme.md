# Sparsnas
Monitor power usage from IKEA Sparsnas sensors using an RTL-SDR dongle. Based on Ludvig Strigeus [original code](https://github.com/strigeus/sparsnas_decoder).

Features
- Supports multiple IKEA Sparsnas sensors simultaneously.
- Idles while not receiving packets which makes it use less resources.
- Can be used without recompiling the source.
- Fixes an issue in the original code which does not take pulses per kWh into account

Requires .net framework 5.0.

## Command line version
Version 0.1 can be downloaded from here:

```cmd
> 
```

## Install via NuGet
To install Sparsnas, run the following command in the Package Manager Console:

```cmd
PM> Install-Package Sparsnas
```

You can also view the package page on [Nuget](https://www.nuget.org/packages/Sparsnas).
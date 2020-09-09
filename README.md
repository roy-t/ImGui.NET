# ImGui.NET for MonoGame

Fork of https://github.com/mellinoe/ImGui.NET with the following changes.

- Ported ImGui.Net to DotNet Core 3.1.
- Replaced types from `System.Numerics` in ImGui.Net with similar types from MonoGame 3.8
- Ported MonoGame example to DotNet Core 3.1.
- Upgraded example to MonoGame 3.8.
- Fixed a bug in the MonoGame example that led everything to be offset with 0.5 pixel, causing unsharp text.
# Allgemein

Vorlage für Dienste, die nach den Prinzipien von Clean Architecture und Domain Driven Design umgesetzt werden sollen.

# Tooling

- .NET SDK 8
- dotnetcli

## Nuget

Pakete mit dem Prefix "ok" werden aus dem Repo "ok" geladen. Alle anderen von Nuget.org.

# Visual Studio Integration

Right now there is no way to install a template package within Visual Studio, to install them on your machine you need to do it using the .NET CLI. More info about how you can do it on section 1.3.

After you have installed the templates via .NET CLI you need to enable the use of templates within Visual Studio.
To enable this option visit the Preview Features options in the Tools > Options menu and look for the Show all .NET Core templates in the New Project dialog checkbox.
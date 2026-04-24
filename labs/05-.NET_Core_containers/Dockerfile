FROM mcr.microsoft.com/dotnet/core/runtime:latest

COPY app/bin/Release/netcoreapp3.1/publish/ app/

ENTRYPOINT ["dotnet", "app/myapp.dll"]
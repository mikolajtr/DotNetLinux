FROM mcr.microsoft.com/dotnet/sdk:5.0
WORKDIR /app
COPY bin/Debug/net5.0/publish .
ENV ASPNETCORE_URLS http://+:5000
EXPOSE 5000
ENTRYPOINT ["dotnet", "App.dll"]
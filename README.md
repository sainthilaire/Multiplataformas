
# Programcion Multiplataformas
#Covid19

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fxamarin%2Fxamarin.exposurenotification%2Fmain%2Fazuredeploy.json)

[Read our Planning Document with more details about how Exposure Notifications work](https://github.com/xamarin/xamarin.exposurenotification/blob/main/Exposure%20Notification%20Planning.pdf)

Cuando una persona ha confirmado un diagnóstico de Covid 19, le informa a su dispositivo, que luego envía los identificadores únicos móviles autogenerados y almacenados localmente de los últimos 14 días a un servicio de back-end proporcionado por la aplicación que implementa la API.

Los dispositivos solicitan continuamente las claves enviadas por personas diagnosticadas desde el servidor backend. Luego, el dispositivo compara estas claves con los identificadores únicos de otros dispositivos con los que ha estado cerca en los últimos 14 días

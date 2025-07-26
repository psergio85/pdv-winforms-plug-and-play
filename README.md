# PDV WinForms Plug & Play (.NET 8)

PDV em **Windows Forms** que:
- Usa **SQLite** (sem servidor).
- O **primeiro PC vira servidor automaticamente** (sobe uma Minimal API).
- Os outros **descobrem o servidor via UDP broadcast** e viram clientes.
- Zero configuração manual.

## Requisitos

- .NET 8 SDK

## Como rodar

```bash
git clone <SEU_REPO_AQUI> pdv-winforms-plug-and-play
cd pdv-winforms-plug-and-play/src/Pdv.App

dotnet restore
dotnet run

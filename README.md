# How to Add the Syncfusion Blazor Split Button to a Blazor WebAssembly App 

## Overview

This sample demonstrates how to add and customize the Syncfusion [Blazor Split Button](https://www.syncfusion.com/blazor-components/blazor-split-button) component in a Blazor WebAssembly application. The application displays a Paste Split Button with a custom icon and provides related paste commands as popup menu items. It also demonstrates icon positioning, horizontal popup styling, component disabling, and dynamic menu-item state management.

## Key Features

- Uses the Syncfusion Blazor `SfSplitButton` component to display a primary Paste action with related commands.
- Defines Paste-related options through `DropDownMenuItems` and `DropDownMenuItem`.
- Positions a custom Paste icon above the button text with `IconCss` and `IconPosition`.
- Configures the Split Button state through the `Disabled` property.
- Handles the `OnOpen` event with `DisableListItem` to disable the Paste Special menu item.
- Arranges and styles the popup menu items horizontally through `CssClass` and custom CSS.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

### Visual Studio 2022

1. Clone or download this repository.
2. Open the solution file:

   `GettingStarted.sln`

3. Restore the NuGet packages by rebuilding the solution.
4. Set the startup project to:

   `GettingStarted.Server`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Open the application URL displayed by Visual Studio.
8. Verify that the customized Paste Split Button is displayed on the page.

### Visual Studio Code

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the executable server project directory:

```bash
cd Server
```

5. Restore the NuGet packages:

```bash
dotnet restore
```

6. Run the project:

```bash
dotnet run
```

7. Open the local URL displayed in the terminal.
8. Verify that the customized Paste Split Button is displayed on the page.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: [Blazor Split Button getting started documentation](https://blazor.syncfusion.com/documentation/split-button/getting-started)

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
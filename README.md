# CMake Tools Multi-Language

## Fork of CMake Tools

[CMake Tools Multi-Language](https://marketplace.visualstudio.com/items?itemName=OpenSpaceLaunchFoundation.cmake-tools-multi-lang) adds `cmake.enabled`, If 'false', CMake Tools skips the workspace, can be set at folder level. E.g. Skip folders that do not use CMake.

This fork was made because the author has a workspace with multiple roots (aka projects). Some of them are Python, Fortran or JavaScript projects and we want to have a setting to disable this extension on those roots. This stops the extension from running CMake build actions, CTest stubs and Intellisense on non-CMake projects!

### Use Case Demo

![Use Case Demo](https://openspacelaunch.github.io/images/cmake-tools-multi-language-demo.gif)

[Closed Pull Request on Upstream Repo](https://github.com/microsoft/vscode-cmake-tools/pull/3646)

[GitHub Repo](https://github.com/openspacelaunch/vscode-cmake-tools-multi-lang)

Maintained by the [Open Space Launch Foundation](https://github.com/openspacelaunch).

---
Original README.md follows:

[CMake Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools) provides the native developer a full-featured, convenient, and powerful workflow for CMake-based projects in Visual Studio Code.

## Important doc links

- [CMake Tools quick start](https://code.visualstudio.com/docs/cpp/CMake-linux)
- [Configure and build a project with CMake Presets](docs/cmake-presets.md)
- [Configure a project with kits and variants](docs/how-to.md#configure-a-project)
- [Build a project with kits and variants](docs/how-to.md#build-a-project)
- [Configure and build a project using tasks](docs/tasks.md)
- [Debug a project](docs/how-to.md#debug-a-project)
- [Configure CMake Tools settings](docs/cmake-settings.md)
- [How to](docs/how-to.md)
- [FAQ](docs/faq.md)
- [Read the online documentation](docs/README.md)
- [Contribute](CONTRIBUTING.md)

## Issues? Questions? Feature requests?

**PLEASE**, if you experience any problems, have any questions, or have an idea
for a new feature, create an issue on [the GitHub page](https://github.com/microsoft/vscode-cmake-tools)!

This extension itself *does not* provide language support for the CMake scripting language.
For that we bundle [this extension](https://marketplace.visualstudio.com/items?itemName=twxs.cmake) which provides the support.
A closed-source extension that provides even better support can also be installed: [CMake Language Support](https://marketplace.visualstudio.com/items?itemName=josetr.cmake-language-support-vscode)

### Microsoft Open Source Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact opencode@microsoft.com with any additional questions or comments.

### Data/Telemetry

This extension collects usage data and sends it to Microsoft to help improve our products and services. Collection of telemetry is controlled via the same setting provided by Visual Studio Code: `"telemetry.enableTelemetry"`. Read our [privacy statement](https://privacy.microsoft.com/en-us/privacystatement) to learn more.

### Credits

This project was started by [@vector-of-bool](https://github.com/vector-of-bool) and is now currently maintained by Microsoft.

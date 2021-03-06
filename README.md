[![Build status](https://ci.appveyor.com/api/projects/status/onshefxnc4g4pv87/branch/staging?svg=true)](https://ci.appveyor.com/project/PowerShell/powershell-docs/branch/staging)

# PowerShell Documentation

Welcome to the PowerShell-Docs repository, housing the official Windows PowerShell documentation. 

## Repository Structure
Each folder in this repo publishes to [MSDN](https://msdn.microsoft.com/en-us/powershell). The folders correspond to the following PowerShell assets:
* [/dsc/](https://msdn.microsoft.com/en-us/powershell/dsc/) is  for the Desired State Configuration feature
* [/gallery/](https://msdn.microsoft.com/powershell/gallery) is for the [PowerShell Gallery](https://www.powershellgallery.com/)
* [/jea/](https://msdn.microsoft.com/powershell/jea/) is for the Just Enough Administration feature
* [/reference/](https://msdn.microsoft.com/powershell/reference/) is for PowerShell module reference across versions 2.0, 3.0, 4.0, 5.0, 5.1, and 6.0
  * This content will be retrieved by the `Get-Help` cmdlet in the future
* [/scripting/](https://msdn.microsoft.com/en-us/powershell/scripting/) is general PowerShell reference content
* [/wmf](https://msdn.microsoft.com/en-us/powershell/wmf/readme) contains release notes for the Windows Management Framework, the package used to distribute new versions of PowerShell to previous versions of Windows. 



## Contributing

We actively merge contributions into this repository via [pull request](https://help.github.com/articles/using-pull-requests/) into the *staging* branch. 
Please note that before you submit a pull request you must [sign a Contribution License Agreement](https://cla.microsoft.com/) to ensure that the community is free to use your submissions.
For more information on contributing, read our [contributions guide](CONTRIBUTING.md).
There is a draft [style guide](./style.md) to review before making contributions.
Please use the Issue and Pull Request templates to help keep documentation consistent across versions. 

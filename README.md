
# MonoGame Templates
This repository is a collection of specialized MonoGame templates to use with Visual Studio 2017 when creating a new project.  

# Included Templates
|  Template Name | Description   |
|---|---|
| MonoGame Multiplatform Project   | This project template will create a new solution with a MonoGame Windows Project, a MonoGame Cross Platform Desktop Project, and a MonoGame Shared Project.  The reference to the shared project is already setup for you in the two individual platform projects.  The Content.mgcb located in the .Windows and .OpenGL projects are both linked to the same single Content.mgcb located in the .Shared project's directory |

# Usage
Complete the following if you'd like to use one of these templates.

1. Clone this repository

```csharp
git clone https://github.com/manbeardgames/monogame-templates.git
```

2. Locate the template you would like to use within the **\zipped\ directory.
3. Copy the zipped template you would like to use to `%UserProfile%\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#\MonoGame` directory.  **Do not unzip it here, just copy over the entier .zip file**

After completing the above steps, when you create a new project in Visual Studio 2017, you should now see that template listed under the MonoGame section.

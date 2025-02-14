# Custom Skins

Files allows you to customize the application with custom skins by modifying xaml resource dictionaries, this allows users to override the default brushes used throughout the app.

Skins are loaded from the ```Skins``` folder in the app's ```LocalState``` folder. A drop-down (Custom skin) is located in Appearance settings that allows you to select a custom skin.

### Quick start

1. Open your text editor of choice, and paste in the template located below. Then, save the file as ```%userprofile%\AppData\Local\Packages\49306atecsolution.FilesUWP_et10x9a9vyk8t\LocalState\Skins\test1.xaml```.

2. Change some of the color values around.

3. Change the selected skin from the appearance settings page.

Files will now use your custom skin. If you add more skins, you can switch between them using the dropdown.

<details>
<summary>
Default template
</summary>

```
<ResourceDictionary
    xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
    xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
    xmlns:BelowWindows10version1809="http://schemas.microsoft.com/winfx/2006/xaml/presentation?IsApiContractNotPresent(Windows.Foundation.UniversalApiContract, 7)"
    xmlns:Windows10version1809="http://schemas.microsoft.com/winfx/2006/xaml/presentation?IsApiContractPresent(Windows.Foundation.UniversalApiContract, 7)">
    <ResourceDictionary.ThemeDictionaries>
        <ResourceDictionary x:Key="Default">
            <!-- Background Resources -->
            <Color x:Key="SolidBackgroundFillColorBase">#FF262738</Color>
            <Color x:Key="SolidBackgroundFillColorSecondary">#FF3F2E4B</Color>
            <Color x:Key="SolidBackgroundFillColorTertiary">#FF332041</Color>
            <Color x:Key="SolidBackgroundFillColorQuarternary">#332041</Color>
            <SolidColorBrush x:Key="SolidBackgroundFillColorBaseBrush" Color="{ThemeResource SolidBackgroundFillColorBase}" />
            <SolidColorBrush x:Key="SolidBackgroundFillColorSecondaryBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="SolidBackgroundFillColorTertiaryBrush" Color="{ThemeResource SolidBackgroundFillColorTertiary}" />
            <SolidColorBrush x:Key="SolidBackgroundFillColorQuarternaryBrush" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <!-- Acrylic Resources -->
            <Color x:Key="SolidBackgroundAcrylic">#332041</Color>
            <!-- Accent Color -->
            <Color x:Key="SystemAccentColor">#8752A8</Color>
            <Color x:Key="SystemAccentColorLight1">#8752A8</Color>
            <Color x:Key="SystemAccentColorLight2">#8752A8</Color>
            <Color x:Key="SystemAccentColorLight3">#8752A8</Color>
            <Color x:Key="SystemAccentColorDark1">#8752A8</Color>
            <Color x:Key="SystemAccentColorDark2">#8752A8</Color>
            <Color x:Key="SystemAccentColorDark3">#8752A8</Color>
            <!-- Tab Resources -->
            <SolidColorBrush x:Key="HorizontalTabControlBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackground" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackgroundSelected" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackgroundPressed" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackgroundPointerOver" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <SolidColorBrush x:Key="TabContainerFillColorPrimary" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="TabContainerFillColorSecondary" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <!-- Status Bar Background -->
            <SolidColorBrush x:Key="StatusBarBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorTertiary}" />
            <!-- File Browser Control Background -->
            <SolidColorBrush x:Key="FileBrowserBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorTertiary}" />
            <!-- Toolbar Background -->
            <SolidColorBrush x:Key="NavigationToolbarBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <!-- PaneHolder -->
            <SolidColorBrush x:Key="PaneHolderPageBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <!--  Sidebar  -->
            <x:Double x:Key="SidebarTintOpacity">0.9</x:Double>
            <x:Double x:Key="SidebarTintLuminosityOpacity">0.9</x:Double>
        </ResourceDictionary>
        <ResourceDictionary x:Key="Light">
            <!-- Background Resources -->
            <Color x:Key="SolidBackgroundFillColorBase">#FFFEF6FF</Color>
            <Color x:Key="SolidBackgroundFillColorSecondary">#FFFBE4FF</Color>
            <Color x:Key="SolidBackgroundFillColorTertiary">#FFF8DFFF</Color>
            <Color x:Key="SolidBackgroundFillColorQuarternary">#C3ADCC</Color>
            <SolidColorBrush x:Key="SolidBackgroundFillColorBaseBrush" Color="{ThemeResource SolidBackgroundFillColorBase}" />
            <SolidColorBrush x:Key="SolidBackgroundFillColorSecondaryBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="SolidBackgroundFillColorTertiaryBrush" Color="{ThemeResource SolidBackgroundFillColorTertiary}" />
            <SolidColorBrush x:Key="SolidBackgroundFillColorQuarternaryBrush" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <!-- Acrylic Resources -->
            <Color x:Key="SolidBackgroundAcrylic">#C3ADCC</Color>
            <!-- Accent Color -->
            <Color x:Key="SystemAccentColor">#948599</Color>
            <Color x:Key="SystemAccentColorLight1">#948599</Color>
            <Color x:Key="SystemAccentColorLight2">#948599</Color>
            <Color x:Key="SystemAccentColorLight3">#948599</Color>
            <Color x:Key="SystemAccentColorDark1">#948599</Color>
            <Color x:Key="SystemAccentColorDark2">#948599</Color>
            <Color x:Key="SystemAccentColorDark3">#948599</Color>
            <!-- Tab Resources -->
            <SolidColorBrush x:Key="HorizontalTabControlBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackground" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackgroundSelected" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackgroundPressed" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <SolidColorBrush x:Key="TabViewItemHeaderBackgroundPointerOver" Color="{ThemeResource SolidBackgroundFillColorQuarternary}" />
            <SolidColorBrush x:Key="TabContainerFillColorPrimary" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <SolidColorBrush x:Key="TabContainerFillColorSecondary" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <!-- Status Bar Background -->
            <SolidColorBrush x:Key="StatusBarBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorTertiary}" />
            <!-- File Browser Control Background -->
            <SolidColorBrush x:Key="FileBrowserBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorTertiary}" />
            <!-- Toolbar Background -->
            <SolidColorBrush x:Key="NavigationToolbarBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <!-- PaneHolder -->
            <SolidColorBrush x:Key="PaneHolderPageBackgroundBrush" Color="{ThemeResource SolidBackgroundFillColorSecondary}" />
            <!--  Sidebar  -->
            <x:Double x:Key="SidebarTintOpacity">0.7</x:Double>
            <x:Double x:Key="SidebarTintLuminosityOpacity">0.7</x:Double>
        </ResourceDictionary>
    </ResourceDictionary.ThemeDictionaries>
</ResourceDictionary>
```
</details> 

You can also use the [Fluent XAML Theme Editor](https://github.com/microsoft/fluent-xaml-theme-editor) to easily modify custom skins.

You can view other skins and contribute your own [here](https://github.com/files-community/custom-skins).

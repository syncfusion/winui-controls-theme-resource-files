# Theme resource files for Syncfusion WinUI - Project Reunion controls

This repository contains the theme resource file (.xaml) of Syncfusion WinUI - Project Reunion controls. You can use these theme resource files to customize the appearance of the controls in the application.

## Customization of Syncfusion WinUI - Project Reunion Controls

Theme resource files containing the resources for Syncfusion WinUI - Project Reunion controls. The steps below describe how to use a theme resources file to customize the appearance of Syncfusion WinUI controls.

1. Download the theme resource file for required controls.
2. Include the resource file in your application.
3. Merge the resource file in your application level.
4. Modify the resource value to change the appearance of the control.

The examples below show how to customize a Ribbon control by using the keys listed below from the ribbon's theme resources file.

{% tabs %}
{% highlight xaml %}

<ResourceDictionary>
    <ResourceDictionary.MergedDictionaries>
        <ResourceDictionary Source="themeresources.xaml" />
    </ResourceDictionary.MergedDictionaries>
</ResourceDictionary>

<SolidColorBrush x:Key="SyncfusionRibbonTabBackgroundPointerOver" Color="White" />
<SolidColorBrush x:Key="SyncfusionRibbonTabBorderBrushSelected" Color="Green" />

{% endhighlight %}
{% endtabs %}
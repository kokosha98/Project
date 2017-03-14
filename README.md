# Project
<Window x:Class="WpfApplication1.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:WpfApplication1"
        mc:Ignorable="d"
        Title="MainWindow" Height="350" Width="525">
    <Grid>
        <Menu IsMainMenu="True">
            <MenuItem Header="_Add">
                <MenuItem Header="_New" />
                <MenuItem Header="_Open" />
            </MenuItem>
            <MenuItem Header="_Edit" />
            <MenuItem Header="_View" />
            <MenuItem Header="_Help" />
        </Menu>
    </Grid>
</Window>

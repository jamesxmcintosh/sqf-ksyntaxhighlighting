# sqf-ksyntaxhighlighting

Install sqf.xml in **org.kde.syntax-highlighting/syntax/**, which is located in your user directory.
Usually it is:

<table>
    <tr>
        <td>For local user</td>
        <td>$HOME/.local/share/org.kde.syntax-highlighting/syntax/</td>
    </tr>
    <tr>
        <td>For Flatpak packages</td>
        <td>$HOME/.var/app/<em>package-name</em>/data/org.kde.syntax-highlighting/syntax/</td>
    </tr>
    <tr>
        <td>For Snap packages</a></td>
        <td>$HOME/snap/<em>package-name</em>/current/.local/share/org.kde.syntax-highlighting/syntax/</td>
    </tr>
    <tr>
        <td>On Windows®</td>
        <td>&#37;USERPROFILE&#37;&#92;AppData&#92;Local&#92;org.kde.syntax-highlighting&#92;syntax&#92;</td>
    </tr>
    <tr>
        <td>On macOS®</td>
        <td>$HOME/Library/Application Support/org.kde.syntax-highlighting/syntax/</td>
    </tr>
</table>

For more details, see ["The Highlight Definition XML Format" (Working with Syntax Highlighting, KDE Documentation)](https://docs.kde.org/?application=katepart&branch=trunk5&path=highlight.html#katehighlight-xml-format).

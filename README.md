# IntelliJ IDEA Settings

My IntelliJ IDEA Settings.  

## File > Settings

### Appearance & Behavior > Appearance

* UI Options
    * Theme: Darcula
* Window Options
    * Show tool window bars: ON
    * Show memory indicator: ON
    * Small labels in editor tabs: ON

### Appearance & Behavior > System Settings

* Startup / Shutdown
    * Reopen last project on startup: OFF
    * Confirm application exit: OFF
* Project Opening: Open project in new window
* Synchronization
    * Use "safe write" (save changes to a temporary file first): OFF

### Appearance & Behavior > Notifications

* File Watcher Messages
    * Popup: No popup

### Keymap

* Keymaps: Akihiro Kondo
    * Main menu
        * Window
            * Editor Tabs
                * Close: Ctrl + F4, Alt + W

### Editor > General

* Mouse
    * Change font size (Zoom) with Ctrl + Mouse Wheel: ON
* Other
    * Ensure line feed at file end on Save: ON

### Editor > General > Auto Import

* Java
    * Insert imports on paste: All
    * Add unambiguous imports on the fly: ON
    * Optimize imports on the fly: ON

### Editor > General > Appearance

* Show method separators: ON
* Show whitespaces: ON
* Show parameter name hints: OFF

### Editor > General > Code Completion

* Code Completion
    * Autopopup documentation: ON

### Editor > General > Code Folding

* Collapse by default
    * File header: OFF
    * Imports: OFF
    * HTML 'style' attribute: OFF
    * XML entities: OFF
    * Data URIs: OFF
    * One line methods: OFF
    * "Closures" (anonymous classes implementing one method, before Java 8): OFF
    * Generic constructor and method parameters: OFF
    * I18n strings: OFF
    * @SuppressWarnings: OFF
    * Android String References: OFF

### Editor > General > Console

* Use soft wraps in console: ON

### Editor > General > Editor Tabs

* Tab Appearance
    * Show tabs in single row: OFF
    * Mark modified tabs with asterisk: ON
* Tab Closing Policy
    * Tab limit: 50

### Editor > Code Style

* Scheme: Akihiro Kondo
    * Line separator (fow new files): Unix and OS X (\n)
    * Java
        * JavaDoc
            * Alignment
                * Align parameter descriptions: OFF
                * Align thrown exception descriptions: OFF
        * Imports
            * General
                * Use fully qualified class names in JavaDoc: Never, use short name and add import
                * Class count to use import with '*': 999
                * Names count to use static import with '*': 999
            * Packages to Use Import with '*'
                * `import java.awt.*`: Delete
                * `import javax.swing.*`: Delete
            * Import Layout
                * `import java.*`: Sort
                * `import javax.*`: Sort
                * `import static java.*`: Sort
                * `import static javax.*`: Sort
                * `<blank line>`: Sort
                * `import all other imports`: Sort
                * `import static all other imports`: Sort
                * `<blank line>`: Sort
    * HTML
        * Other
            * Align attributes: OFF
    * Kotlin
        * Imports
            * Top-level Symbols
                * Use single name import
            * Java Statics and Enum Members
                * Use single name import
            * Packages to Use Import with '*'
                * `import java.util.*`: Delete
                * `import kotlinx.android.synthetic.*`: Delete
    * XML
        * Other
            * Align attributes: OFF

### Editor > Inspections

* Profile: Akihiro Kondo
    * BashSupport
        * Missing include file: OFF
        * Simple variable usage: OFF
        * Unresolved variable: OFF
    * Ignore
        * Unused entry: OFF
    * Java
        * Abstraction issues
            * 'Optional' used as field or parameter type: OFF
        * Declaration redundancy
            * Actual method parameter is the same constant: OFF
            * Declaration access can be weaker: OFF
            * Declaration can have final modifier: OFF
            * Method can be void: OFF
            * Method returns the same value: OFF
            * Unused declaration: ON
                * Options
                    * Members to report
                        * Classes: "Package-private": ON
                        * Inner classes: "Package-private": ON
                        * Fields: "Package-private": ON
                        * Methods: "Package-private": ON
                        * Parameter in "Package-private" methods: ON
    * Kotlin
        * Can be replaced with function reference: ON
        * Unuse symbol: OFF
    * Properties Files
        * Unused Property: OFF
    * Spelling
        * Typo: OFF

### Editor > File and Code Templates

* Includes
    * File Header: (Customize)

### Editor > File Encodings

* Project Encoding: UTF-8
* Properties Files (*.properties)
    * Default encoding for properties files: UTF-8

### Editor > File Types

* HTML
    * `*.jst`: Add
* Properties
    * `*.factories`: Add

### Plugins

* Ant Support: Disable
* CVS Integration: Disable
* Eclipse Integration: Disable
* hg4idea: Disable
* Settings Repository: Disable
* Subversion Integration: Disable
* TestNG-J: Disable

### Version Control > Confirmation

* When files are created: Do not add
* When files are deleted: Do not remove

### Version Control > Ignore Files Support

* User templates
    * Example user template: Delete

### Version Control > Git

* Path to Git executable: (Path on my computer)

### Build, Execution, Deployment > Build Tools > Maven > Importing

* Import Maven projects automatically: ON
* Automatically download
    * Sources: ON
    * Documentation: ON

### Build, Execution, Deployment > Compiler

* Build project automatically: ON

### Build, Execution, Deployment > Compiler > Annotation Processors

* Default
    * Enable annotation processing: ON

### Build, Execution, Deployment > Compiler > Kotlin Compiler

* Kotlin to JVM
    * Target JVM version: 1.8

### Build, Execution, Deployment > Debugger

* Hide debug window on process termination: ON

### Build, Execution, Deployment > Coverage

* When new coverage is gathered: Replace active suites with the new one

### Languages & Frameworks > Schemas and DTDs

* Ignored Schemas and DTDs
    * "http://maven.apache.org/DECORATION/1.7.0": Add
    * "http://www.puppycrawl.com/dtds/configuration_1_3.dtd": Add
    * "http://www.puppycrawl.com/dtds/suppressions_1_1.dtd": Add
    * "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd": Add

### Languages & Frameworks > Schemas and DTDs > Default XML Schemas

* XML Schema version: XML Schema 1.1

### Languages & Frameworks > Markdown > Preview

* Preview browser: JavaFX WebView
* Default editor layout: Show editor only

## File > Project Structure

### Project Settings > Project

* Project SDK: (Path on my computer)

## Help > Tip of the Day

* Show Tips on Startup: OFF

## File > Settings (manually)

### Plugins

* .ignore: Install
* BashSupport: Install
* CodeGlance: Install
* Lombok Plugin: Install
* Markdown support: Install

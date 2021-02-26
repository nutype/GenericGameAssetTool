# GenericGameAssetTool
Game-agnostic set of tools/libraries for reading and manipulating various game asset files for usage by other toolkits which target particular games.  Think of this as just a generic collection of tools and libraries which you can use to do the "heavy lifting" of reading/manipulating game asset files so you can focus more on the front-end-type stuff for your specific toolkit needs.

# Why C# and not C++?
Basically, because:

* This is geared more towards toolkits and **not** actual "game engine" -type development (in which case, you probably _should_ be using C++ instead).
* This was written using .NET 5, so there's the overall goal, if you will, of not only creating a game-agnostic set of tools/libraries, but also a _platform-agnostic_ set of tools/libraries (i.e., you could _potentially_ use these tools/libaries on other platforms, such as Linux, and not just on Windows).

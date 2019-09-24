# JSHTML Language Support

[JSHTML Language Support] adds support for JavaScript HTML files in **Visual Studio Code**.

```jshtml
<!doctype html>
<h1>
  Awesome ${true ? 'hello' : 'world'}!
</h1>
<ul>
  ${launches.map(launch => (
    <li>{launch.mission_name}!</li>
  ))}
</ul>
```

This syntax is applied to `.jshtml` files. It is also applied to `jshtml` code blocks in Markdown, and also to `<script type="text/jshtml>` code blocks in HTML.

## Installation

1. Open the command palette and select **Extensions: Install Extensions**
2. Search for **JSHTML Language Support**
3. Click **Install**

[JSHTML Language Support]: https://github.com/jsxtools/jshtml-language

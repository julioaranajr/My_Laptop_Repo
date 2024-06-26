# Best practices for repositories

## Learn how to use repositories most effectively. 
In this article:
- Create a README file
- Favor branching over forking
- Use Git Large File Storage

## What is it?
The README.md file is a text file that introduces and explains a project.<br>
It contains information that is commonly required to understand what the project is about.<br>

## Why should I make it?
It's an easy way to answer questions that your audience will likely have regarding how to install<br>
and use your project and also how to collaborate with you.<br>

## Who should make it?
Anyone who is working on a programming project, especially if you want others to use it or contribute.

## When should I make it?
Definitely before you show a project to other people or make it public.<br> 
You might want to get into the habit of making it the first file you create in a new project.<br>

## Where should I put it?
In the top level directory of the project.<br>
This is where someone who is new to your project will start out.<br>
Code hosting services such as GitHub, Bitbucket, and GitLab will also look for your README and<br>
display it along with the list of files and directories in your project.<br>

## How should I make it?
While READMEs can be written in any text file format, the most common one that is used nowadays is Markdown.<br> 
It allows you to add some lightweight formatting. You can learn more about it at the CommonMark website,<br> 
which also has a helpful reference guide and an interactive tutorial.<br>
- Some other formats that you might see are plain text, reStructuredText (common in Python projects), and Textile.
- You can use any text editor. There are plugins for many editors (e.g. Atom, Emacs, Sublime Text, Vim, and Visual Studio Code) that allow you to preview Markdown while you are editing it.
- You can also use a dedicated Markdown editor like Typora or an online one like StackEdit or Dillinger.
- You can even use the editable template below.

## Example:

### Foobar
- Foobar is a Python library for dealing with word pluralization.

### Installation:
- Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

#### Usage:

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

- Pull requests are welcome.<br> 
- For major changes, please open an issue first to discuss what you would like to change.<br>
- Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

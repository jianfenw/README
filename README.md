# README
This project gives a demo about the interesting README.md file. You may notice that you should have a README.md file, but do you know how to write a better README.md file?<br>
README.md is a text file in Markdown format. Markdown is created to easily edit your blog. However, the Markdown used by github is a modified version of the standard Markdown and is called Github Flavored Markdown (GFM).

Create a new project and write your own README.md for your project! You can even edit it online and see the changes immediately (click the "Preview" bottom).<br>

# How to create a title
Large title:<br>
\# + your words

Middle title:<br>
your words<br>
\----

You may notice there is a line under the words. It means you have created a new title. You can also create a line to seperate paragraghs by type a "#".

# How to edit text

## Linefeed
Typing a 'Enter' does not make any change. Unlike a normal texteditor, you have to use \<br> for linefeed. Also, you can seperate paragraphs with a single line and create a single line gap.
```
I want a linefeed here<br>Yes, I get it.
```
I want a linefeed here<br>Yes, I get it.

## Single line text
Add two 'Tab' to make a single line text.
## Highlight words

If you want to highlight some words in your README.md, you can use \`\` to wrap the words that you'd like to highlight.<br>
For example:
```
README is `great`!
```
README is `great`!

## External weblink

[your words]( your weblink "your mouseover")

Here is an example:
```
[google](http://www.google.com "google")
```
[google](http://www.google.com "google")

## Some marks

Use '*' to create a solid dot. For example:
```
* First
* Second
```
* First
* Second

Also, you can use 'Tab' to create different layers. For example:
```
* First
	* First-sub-1
		* First-sub-1-sub-1
```
* First
	* First-sub-1
		* First-sub-1-sub-1

## Tree struct

\>Earth<br>
\>>US<br>
\>>>California<br>
\>>>>Los Angeles<br>
It looks like ...
>Earth
>>US
>>>California
>>>>Los Angeles

## External photo

Use ! + [img Tag](img URL "img mouseover")
```
![Cute Cat](https://s-media-cache-ak0.pinimg.com/736x/ba/03/23/ba03237a6d6499f0e2633314826e1526--cutest-animals-baby-animals.jpg "Cute Cat")
```
![Cute Cat](https://s-media-cache-ak0.pinimg.com/736x/ba/03/23/ba03237a6d6499f0e2633314826e1526--cutest-animals-baby-animals.jpg "Cute Cat")

Also, you can substitute the external img URL with your own img which is stored in your github repository if you believe it's more 'stable'.

## External photo with an external weblink

Refer to the 'External weblink' and 'External Photo' part. You can combine them together and load a external photo with an external weblink.

## Code

Wrap your code with \```. I will give two examples about the C code and bash command code.

\```c<br>
int main(argc, argv[]){ // C code <br>
	return 0; <br>
} <br>
\```

```c
int main(argc, argv[]){
	return 0;
}
```

\```Bash<br>
echo "Hello World!"<br>
\```

```Bash
echo "Hello World!"
```

#
Please Star this project if you find it interesting and helpful<br>
[My Personal Page](http://jwangee.github.io "jwangee")<br>
copyright @ jwangee








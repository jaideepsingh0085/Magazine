# Magazine
![Screenshot 2023-09-21 234147](https://github.com/jaideepsingh0085/Magazine/assets/128147644/213b9b26-47f8-4747-b646-ea4760f9f174)
![Screenshot 2023-09-21 234157](https://github.com/jaideepsingh0085/Magazine/assets/128147644/be3c1d82-3374-42c1-b00d-1a379b383b01)
![Screenshot 2023-09-21 234206](https://github.com/jaideepsingh0085/Magazine/assets/128147644/b7bebd66-8a22-47fb-b17a-fbbee108d97d)
![Screenshot 2023-09-21 234213](https://github.com/jaideepsingh0085/Magazine/assets/128147644/8123440c-acd3-447d-98f9-ab1a2f20ccaa)
![Screenshot 2023-09-21 234219](https://github.com/jaideepsingh0085/Magazine/assets/128147644/63a19e68-09ec-4670-a0b8-b1d10e89b97b)
![Screenshot 2023-09-21 234228](https://github.com/jaideepsingh0085/Magazine/assets/128147644/859cb7c8-1021-43ea-ac72-0a9017a524d3)
![Screenshot 2023-09-21 234234](https://github.com/jaideepsingh0085/Magazine/assets/128147644/570cea1d-1424-4c4d-bb2a-8f2119066813)
![Screenshot 2023-09-21 234252](https://github.com/jaideepsingh0085/Magazine/assets/128147644/d1700310-2ca5-4554-aa04-b1a619b235e2)
![Screenshot 2023-09-21 234300](https://github.com/jaideepsingh0085/Magazine/assets/128147644/92a9e680-eaf7-4fd1-a9b4-b5d80fe4174d)
![Screenshot 2023-09-21 234306](https://github.com/jaideepsingh0085/Magazine/assets/128147644/22aba648-012d-4ef6-b340-68481b8a611b)
![Screenshot 2023-09-21 234312](https://github.com/jaideepsingh0085/Magazine/assets/128147644/50f7e1da-4043-457e-be88-b85e3bf3ea53)

Hosted Link : https://jaideepsingh0085.github.io/Magazine/

HTML :
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the HTML document and specifies the language as English.
<head>: Contains metadata about the HTML document.
<meta charset="UTF-8">: Sets the character encoding to UTF-8 for proper text rendering.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>: Sets the title of the web page displayed in the browser tab.
<link href="./style.css" rel="stylesheet">: Links an external CSS file called "style.css" for styling.
<link href="https://fonts.googleapis.com/css?family=Anton%7CBaskervville%7CRaleway&display=swap" rel="stylesheet">: Links external fonts from Google Fonts.
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css">: Links external FontAwesome icons for use in the page.
<body>: Contains the visible content of the web page.
<main>: Represents the main content section of the page.
<section class="heading">: Defines a section for the heading content.
<header class="hero">: Represents the header section containing the hero content.
<img src="..." alt="..." loading="lazy" class="hero-img">: Embeds an image with source, alt text, and lazy loading.
<h1 class="hero-title">: Defines a level 1 heading for the hero title.
<p class="hero-subtitle">: Represents a paragraph for the hero subtitle.
<div class="author">: Defines a container for author-related information.
<p class="author-name">: Represents the author's name.
<a href="..." target="_blank" rel="noreferrer">: Creates a hyperlink with specified attributes.
<p class="publish-date">: Displays the publication date.
<div class="social-icons">: Defines a container for social media icons.
<a href="...">: Creates hyperlinks to social media profiles.
<i class="fab fa-facebook-f">: Embeds a FontAwesome icon for Facebook.
<section class="text">: Defines a section for text content.
<p class="first-paragraph">: Represents the first paragraph of the text.
<p>: Represents paragraphs of text.
<blockquote>: Defines a blockquote section for quoted content.
<hr />: Inserts a horizontal rule within the blockquote.
<p class="quote">: Displays a quoted text within the blockquote.
<section class="text text-with-images">: Defines a section for text with images.
<article class="brief-history">: Represents an article within the section.
<h3 class="list-title">: Defines a level 3 heading for the list title.
<p>: Represents paragraphs of text within the article.
<ul class="lists">: Defines an unordered list within the article.
<li>: Represents list items within the unordered list.
<h4 class="list-subtitle">: Defines a level 4 heading for list subtitles.
<aside class="image-wrapper">: Defines a side content section for images.
<img src="..." alt="..." loading="lazy" class="image-1">: Embeds images with sources, alt text, and lazy loading.
<blockquote class="image-quote">: Defines a blockquote section for quoted image content.
<img src="..." alt="..." loading="lazy" class="image-2">: Embeds additional images.
<img src="..." alt="..." loading="lazy" class="image-3">: Embeds more images.

CSS :
*, ::before, ::after: Applies padding, margin, and box-sizing to all elements, pseudo-elements before and after.

html: Sets the base font size for the entire HTML document to 62.5% of the default.

body: Styles the overall appearance of the webpage, including font family, text color, and background color.

h1: Specifies the font family for level 1 headings.

h2, h3, h4, h5, h6: Specifies the font family for various heading levels.

a: Styles hyperlinks, removing text decoration and setting text color.

main: Uses grid layout to structure the main content area with specific column widths and row gaps.

img: Sets images to be responsive with a cover aspect ratio.

hr: Styles horizontal rules, adding margin and border properties.

.heading: Styles a specific section with grid layout, defining columns and row gaps.

.text: Styles text content, setting font size, letter spacing, column width, and text alignment.

.hero: Styles the hero section, extending it across columns and positioning it.

.hero-title: Styles the hero's main title, including text alignment and color.

.hero-subtitle: Styles the hero's subtitle with specific font size and color.

.author: Styles the author's information section, including font size and family.

.author-name a:hover: Adds a background color when hovering over author's name links.

.publish-date: Sets the color for the publication date with opacity.

.social-icons: Styles social media icons with grid layout, font size, and alignment.

.first-paragraph::first-letter: Styles the first letter of the first paragraph, adjusting font size, color, and float.

.quote: Styles quotes with specific color, font size, and alignment.

.quote::before and .quote::after: Adds quotation marks before and after the quoted text.

.text-with-images: Styles sections with text and images using grid layout and column gap.

.lists: Styles unordered lists, removing list-style and adding margin.

.lists li: Styles list items with margin for spacing.

.list-title and .list-subtitle: Sets specific text color for list titles and subtitles.

.image-wrapper: Styles the container for images using grid layout and gap.

.image-1 and .image-3: Styles specific images within the image wrapper.

Media Queries (responsive design): Adjusts font sizes, social icons, and layout for various screen widths using media queries.

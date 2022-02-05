# Cloning Netflix
## History
I've been enrolled in a bootcamp at Digital Innovation One.

One of their assignments was to build a Netflix Clone with your own different theme and purpose.

So I decided that I wanted to create a streaming platform **focused on Documentaries**.

**The name: Realscreen**

**The logo: Reality is awesome**

## Technologies Used

Basically, it's all HTML5 and CSS3.

For the carousel, I used a JQuery plugin called Owl Carousel 2.
You can find it to download at this link:

[Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/)

### You'll need some files inside the downloaded folder:

- JavaScript: 'jquery.min.js' AND 'owl.carousel.min.js'
- CSS:  'owl.carousel.min.css' AND 'owl.theme.default.min.css'
#### OBS:

- Make sure ALL your script tags in HTML5 are declared at the end of your code, right before the closing BODY tag.
 Ex:
```
  <body>
      <!-- a lot of code here-->
  
  
      <!-- your scripts at the end -->
      <script src="pathname"></script>
      <script></script>
      <script></script>
  </body>
```

- Make sure ALL your CSS links in your HTML file are declared and have the correct directory path

## Difficulties

I could classify my difficulties at this challenge as two:

- Responsivity
- Different image heights

#### Responsivity

I think it's always a problem to solve in every project, since we want the user to have a beautiful and usable interface on all kind of devices.
So I started with the Mobile-First concept, designing the responsivity from a 250px wide screen to wider ones.
And it really worked. It's more productive thinking about the mobile first than thinking only on Desktop screen to go to Mobile.

#### Different Image Heights

Since I referred the images with outside links, they had different heights on every screen.

So I sett some changes on CSS:

```
.image-div-class-name{
  display: block;

    height: 27em; /*sets the same height for every picture inside the carousel*/
    width: 100%;
}
```
and it worked!

# That's all Folks
## Thank you for reading this README
### I hope you understood it and enjoyed it too

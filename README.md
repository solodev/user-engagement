# user-engagement
Gaining customers is the start, retaining them is another matter. A user engagement bar provides all of the means of engagement you offer in one box, making it easier for customers to connect with your business. This article provides the code to add a user engagement bar to your website.

## Tutorial

For detailed instructions, view Solodev's [Adding a User Engagement Bar to your Website](https://www.solodev.com/blog/web-design/adding-a-user-engagement-bar-to-your-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/xfwywsyo/).

## HTML

The user engagement bar contains the following basic HTML markup.

```
<section class="ct-newsletter-section hidden-print">
   <div class="container">
      <h2 class="ct-section-header">
         CONNECT WITH WEBCORPCO
      </h2>
      <div class="ct-newsletter-inline">
         <a class="ct-newsletter-inline__facebook" target="_blank" href="/"><i class="fa fa-facebook"></i><span>facebook</span></a> <a class="ct-newsletter-inline__twitter" target="_blank" href="/"><i class="fa fa-twitter"></i><span>twitter</span></a>
         <div class="ct-newsletter-inline__form">
            <form class="ct-newsletter" action="/" enctype="multipart/form-data" method="post" name="contentForm">
              <label for="newsletter">Get Updates from WEBCORPCO in your inbox</label>
               <div class="form-inline">
                  <input id="newsletter" name="newsletter" placeholder="Enter Your Email Address" type="text"> <button class="btn btn-dark" type="submit">SEND</button>
               </div>
            </form>
         </div>
      </div>
   </div>
</section>
```

## CSS

All required CSS is in connect-bar.css

## External Includes

This tutorial contains the following third party resources.
```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css">
<link rel="stylesheet" href="connect-bar.css">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">

<script src="https://code.jquery.com/jquery-2.2.0.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```

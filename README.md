# jquery-form-validation
Keep your forms validating properly with jQuery validator

## Tutorial
For detailed instruction's, view Solodev's [Using jQuery Validator for Your Form Validation](https://www.solodev.com/blog/using-jquery-validator-for-your-form-validation.stml) article.

## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/d1vubqr0/8/).

## HTML

The tutorial contains the following basic HTML markup.

```
 <section class="p-4 w-100 w-lg-350p w-xl-400p">
                <form action="/action" data-toggle="validator" enctype="multipart/form-data" id="top-signup-form" method="post" novalidate="novalidate">
                  <div class="form-group pb-2">
                    <label for="firstName">First name <span class="text-coral">*</span>
                    </label>
                    <input aria-label="Sign Up First Name" class="form-control border-top-1 border-left-1 border-right-1" id="firstName" name="firstName" placeholder="Type your first name" required="required" type="text" data-kwimpalastatus="alive" data-kwimpalaid="1569934474905-2">
                    <label id="firstName-error" class="error" for="firstName"></label>
                  </div>
                  <div class="form-group pb-2">
                    <label for="lastName">Last name <span class="text-coral">*</span>
                    </label>
                    <input aria-label="Sign Up Last Name" class="form-control border-top-1 border-left-1 border-right-1" id="lastName" name="lastName" placeholder="Type your last name" required="required" type="text" data-kwimpalastatus="alive" data-kwimpalaid="1569934474905-3">
                    <label id="lastName-error" class="error" for="lastName"></label> 
                  </div>
                  <div class="form-group pb-2">
                    <label for="email">Email <span class="text-coral">*</span>
                    </label>
                    <input aria-label="Sign Up Email" class="form-control border-top-1 border-left-1 border-right-1" id="email" name="email" placeholder="you@example.com" required="required" type="email" data-kwimpalastatus="alive" data-kwimpalaid="1569934474905-4">
                    <label id="email-error" class="error" for="email"></label>
                  </div>
                  <div class="pt-1">
                    <input class="btn w-100 mt-3 mb-1" id="submit" type="submit" value="Sign Up">
                  </div>
                </form>
  </section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/jquery-validation@1.19.1/dist/jquery.validate.min.js"></script>
```

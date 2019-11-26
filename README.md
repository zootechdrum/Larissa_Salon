# Description
I created this for my hair salon friend Larissa Gomez. This projet did not end up going to the wild. Nevertheless it was a good learning experiance as it uses the latest classes from BootStrap 4.0

## Technologies Used

1. Bootstrap 4.0
2. CSS
3. HTML 5

![Gif of website](larissa.gif)

## Snippet of Code 

I really found it interesting the pre-determined classes like d-none which hides elements as soon as the sections seed to resize 
according the screen size. I also like the mb-5 classes which will add margin bottom of 5px. Very simple to use. 

```HTML
      <section class="container-fluid px-0 content">
        <div class="row align-items-center">
            <div class="col-md-6 text-center ">
                <div class="row justify-content-center">
                    <div class="col-10 col-lg-8 blurb mb-5 mb-md-0" >
                        <h2>ABOUT</h2>
                        <img src="images/icon.png" alt="" class="d-none d-lg-inline">
                        <p class="lead">Lorem Ipsum is simply dummy text of the printing and 
                            typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since
                            he 1500s, when an unknown printer took a galley of type and scrambled it to make a type 
                            specimen book. It has survived not only five centuries, but also the leap into electroni</p>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <img src="images/salon_tools.jpg" class="img-fluid"/>
            </div>
        </div>
      </section>


```

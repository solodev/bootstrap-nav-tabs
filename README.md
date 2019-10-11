# bootstrap-nav-tabs
Condense your relevant news and events into a single component with the use of nav tabs.

## Tutorial
For detailed instruction's, view Solodev's [How to Use Bootstrap Nav Tabs to Showcase Upcoming News & Events](https://www.solodev.com/blog/how-to-use-bootstrap-nav-tabs-to-showcase-upcoming-news-events.stml) article.

## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/6f51eshx/3/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="section-news">
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <h2 class="text-center">News &amp; Events</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-12">
            <ul class="nav nav-tabs" id="myTab" role="tablist">
              <li class="nav-item active" role="presentation">
                <a class="nav-link active" id="home-tab" data-toggle="tab" role="tab" aria-controls="events" aria-selected="true" href="#events">Events</a>
              </li>
              <li role="presentation" class="nav-item">
                <a class="nav-link" id="profile-tab" data-toggle="tab" role="tab" aria-controls="news" aria-selected="true" href="#news">News</a>
              </li>
              <li role="presentation" class="nav-item">
                <a class="nav-link" id="articles-tab" data-toggle="tab" role="tab" aria-controls="articles" aria-selected="true" href="#articles">Articles</a>
              </li>
            </ul>
          </div>
        </div>
        <!--.row-->
        <div class="row">
          <div class="col-sm-12">
            <div class="tab-content" id="myTabContent">
              <div aria-label="events-tab" class="tab-pane active" id="events">
                <div class="col-md-6 col-xs-12">
                  <div class="article">
                    <span>17</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">ASTRONAUT LEADERSHIP TRAINING</a></h3>
                      <p>September 17, 2020</p>
                      <p>1:00pm - 5:00pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>23</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('');" href="#">ASTRONAUT LEADERSHIP TRAINING</a></h3>
                      <p>July 23, 2020</p>
                      <p>1:00pm - 5:00pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>16</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('');" href="#">ASTRONAUT LEADERSHIP TRAINING</a></h3>
                      <p>April 16, 2020</p>
                      <p>1:00pm - 5:00pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                </div>
                <!--.col-->
                <div class="col-md-6 col-xs-12 second-column">
                  <div class="article">
                    <span>16</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('');" href="#">ASTRONAUT LEADERSHIP TRAINING</a></h3>
                      <p>April 16, 2020</p>
                      <p>1:00pm - 5:00pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>13</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('');" href="#">ASTRONAUT LEADERSHIP TRAINING</a></h3>
                      <p>February 13, 2020</p>
                      <p>1:00pm - 5:00pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>17</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">ASTRONAUTICON</a></h3>
                      <p>September 17, 2020</p>
                      <p>8:00am - 12:00pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                </div>
                <!--.col-lg-6-->
              </div>
              <!--#events-->
              <div aria-label="news-tab" class="tab-pane" id="news">
                <div class="col-md-6 col-xs-12">
                  <div class="article">
                    <span>08</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">LunarXP Wins Space Innovator of the Year Award</a></h3>
                      <p>October 08, 2019</p>
                      <p>12:43pm - 12:00am</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>02</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">New Spending Bill Expands Funding for Space Exploration</a></h3>
                      <p>October 02, 2019</p>
                      <p>9:57am - 12:00am</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>01</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">LunarXP Sets Target for First Mars Landing in 2030</a></h3>
                      <p>October 01, 2019</p>
                      <p>10:27am - 12:00am</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                </div>
                <!--.col-lg-6-->
                <div class="col-md-6 col-xs-12 second-column">
                  <div class="article">
                    <span>01</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">Habitat Offerings to Include New Hydroponics Lab</a></h3>
                      <p>October 01, 2019</p>
                      <p>10:27am - 12:00am</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>30</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">LunarXP Voted Best Mars Mission</a></h3>
                      <p>September 30, 2019</p>
                      <p>4:29pm - 5:30pm</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <span>27</span>
                    <div class="title">
                      <h3><a onclick="documentTrack('#');" href="#">New Features on the Valkyrie-1 Spacecraft</a></h3>
                      <p>September 27, 2019</p>
                      <p>3:51pm - 10:18am</p>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                </div>
                <!--.col-lg-6-->
              </div>
              <!--#news-->
              <div aria-label="articles-tab" class="tab-pane" id="articles">
                <div class="col-md-6 col-xs-12">
                  <div class="article">
                    <div class="title">
                      <h3>
                        <i class="far fa-newspaper"></i><a target="_blank" href="#">Habitat Offerings to Include New Hydroponics Lab</a>
                      </h3>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <div class="title">
                      <h3>
                        <i class="far fa-newspaper"></i><a target="_blank" href="#">An Inside Look into Building The Talon-2 Spacecraft</a>
                      </h3>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <div class="title">
                      <h3>
                        <i class="far fa-newspaper"></i><a target="_blank" href="#">LunarXP Voted Best Mars Mission</a>
                      </h3>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                </div>
                <!--.col-lg-6-->
                <div class="col-md-6 col-xs-12 second-column">
                  <div class="article">
                    <div class="title">
                      <h3>
                        <i class="far fa-newspaper"></i><a target="_blank" href="#">New Features on the Valkyrie-1 Spacecraft</a>
                      </h3>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <div class="title">
                      <h3>
                         <i class="far fa-newspaper"></i><a target="_blank" href="#">Astronaut Leadership Training Has Started</a>
                      </h3>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                  <div class="article">
                    <div class="title">
                      <h3>
                         <i class="far fa-newspaper"></i><a target="_blank" href="#">LunarXP Seeks to Fill Immediate Colonial Positions</a>
                      </h3>
                    </div>
                    <!--.title-->
                  </div>
                  <!--.article-->
                </div>
                <!--.col-lg-6-->
              </div>
              <!--#press-->
            </div><!-- tab content-->
          </div><!-- col-->
        </div><!-- row-->
        <div class="row">
          <div class="col-sm-12">
            <a class="btn btn-white" href="#">See All Events</a>
          </div>
        </div><!-- col-->
      </div>
      <!--.row-->
    </section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```

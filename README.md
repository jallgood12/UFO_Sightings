# UFO_Sightings

## Overview 

The purpose of this project was to create a website that displays different UFO sighting around the US and Canada. On this webpage one should be able to input and filter data. HTML is used for the general structure and Bootstrap will determine how it looks.

## Results

The code to create each part of the webpage is shown below:

### Initial Dependencies

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UFO Finder</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous" />
    <link rel="stylesheet" href="static/css/style.css">
</head>

### Navigation Bar 

<div class="wrapper">
        <nav class="navbar navbar-dark bg-dark navbar-expand-lg">
            <a class="navbar-brand" href="index.html">UFO Sightings</a>
        </nav>
    </div>

### Page Header 

<div class="jumbotron">
        <h1 class="display-4">The Truth is Out There</h1>
    </div>
    
    
### Article Title 

<div class="container-fluid">
        <div class="row">
            <div class="col-md-3">
                <div>
                    <h3>UFO Sightings: Fact or Fancy?</h3>
                </div>
                <div>
                    <h3><small>Ufologists Weigh In</small></h3>
                </div>
            </div>
            

### Article Paragraph 

<div class="container-fluid">
    .
    .
    .
    <div class="col-md-9">
                <p>Are we alone in the universe? For millennia, humans have turned to the sky to answer this question.
                    Now, thanks to research generously funded by W. Avy, a UFO-enthusiast and amateur ufologist, we can
                    supplement our sky-searching with data analysis.

                    "The release of this analysis is well-timed: It coincides with the celebration of World UFO Day,
                    which is a moment for ufologists around the world to connect, relax, and sample a range of
                    UFO-themed snacks," said Dr. Ursula F. Olivier, the world's preeminent expert on circular sightings.
                    "Citizen-scientists can be especially helpful in both cataloguing sightings—which is hugely helpful
                    for us in our search for aliens—and in helping us celebrate the work that has already been done,
                    such as this data visualization project, which will help us raise awareness of the ubiquity of
                    sightings!"

                    Not everyone is ready to celebrate, however. Local CEO and vocal anti-alien activist V. Isualize
                    reached out to our reporters to go on record as firmly opposed to any attempts to provide access to
                    this data. "If there are aliens, they certainly would like to be left alone," she stated, before
                    directing us to the Leave Aliens Alone (LAA) community engagement initiative she founded and funds.

                    So what do YOU think? Are we alone in the universe? Are aliens trying to contact us, or do they want
                    to be left alone? Dig through the data yourself, and let us know what you see.</p>
            </div>
            

### Filters for the Table 

<div class="container-fluid">
        <div class="row">
            <div class="col-md-3">
                <form class="bg-dark">
                    <p>Filter Search</p>
                    <!-- Date Filter Field -->
                    <li class="list-group-item bg-dark">
                    <label for="date">Enter Date</label>
                    <input type="text" placeholder="1/10/2010" id="datetime" />
                    </li>
                    <!-- City Filter Field -->
                    <li class="list-group-item bg-dark">
                    <label for="city">Enter City</label>
                    <input type="text" id="city" />
                    </li>
                    <!-- State Filter Field -->
                    <li class="list-group-item bg-dark">
                    <label for="state">Enter State</label>
                    <input type="text" id="state" />
                    </li>
                    <!-- Country Filter Field -->
                    <li class="list-group-item bg-dark">
                    <label for="country">Enter Country</label>
                    <input type="text" id="country" />
                    </li>
                    <!-- Shape Filter Field -->
                    <li class="list-group-item bg-dark">
                    <label for="shape">Enter Shape</label>
                    <input type="text" id="shape" />
                    </li>
                </form>
            </div>
            
            
 ### Table of Sightings Data 
 
 <div class="col-md-9">
                <div class="col-md-9">
                    <table class="table table-striped">
                        <thead>
                            <tr>
                                <th>Date</th>
                                <th>City</th>
                                <th>State</th>
                                <th>Country</th>
                                <th>Shape</th>
                                <th>Duration</th>
                                <th>Comments</th>
                            </tr>
                        </thead>
                        <tbody></tbody>
                    </table>
                </div>
            </div>
            
            
 ### Final Dependencies
 
 <script src="https://cdnjs.cloudflare.com/ajax/libs/d3/4.11.0/d3.js"></script>
<script src="static/js/data.js"></script>
<script src="static/js/app.js"></script>





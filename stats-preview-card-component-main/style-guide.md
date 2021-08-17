# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very dark blue (main background): hsl(233, 47%, 7%)
- Dark desaturated blue (card background): hsl(244, 38%, 16%)
- Soft violet (accent): hsl(277, 64%, 61%)

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%)
- Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)
- Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400






.container{
    position: relative;
    display: grid;
    width: 70%;
    height: 450px;
    background: hsl(244, 38%, 16%);
    margin: auto;
    top: 100px;
    border-radius: 5px;
    grid-template-areas: "a1 a1 a1 a1 a1 a6 a6"
                         "a1 a1 a1 a1 a1 a6 a6"
                         "a2 a2 a2 a2 a2 a6 a6"
                         "a3 a3 a4 a4 a5 a6 a6";
}

<h1 class="title">Get insights that help<br>your business grow.</h1>

            <p class="text">Discover the benefits of data analytics and make<br>better decisions regarding revenue,
                customer<br>experience, and overall efficiency.</p>

            <div class="stats1">
                <h1>10k+</h1>
                <p>companies</p>
            </div>

            <div class="stats2">
                <h1>314</h1>
                <p>templates</p>
            </div>

            <div class="stats3">
                <h1>12m+</h1>
                <p>queries</p>
            </div>

            <div class="img">
                <img src="./images/image-header-desktop.jpg">
            </div>



.img{
    background: hsl(277, 64%, 61%);
    position: relative;
    height: 450px;
}
img{
    opacity: 70%;
    position: relative;
    height: 100%;
    width: 100%;
}
.title{
    grid-area: a1;
    padding: 5%;
}
.text{
    grid-area: a2;
    padding: 5%;
}
.stats1{
    grid-area: a3;
    margin-left: 13%;
    margin-top: 20px;
}
.stats2{
    grid-area: a4;
}
.stats3{
    grid-area: a5;
}
.img{
    grid-area: a6;
}
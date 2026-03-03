# Day-5-of-html-code-
Resturant  manu by html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resturant manu</title>
</head>
<body>
    <div class="container" style="display: block; height: 470px; width: 450px; border: 1px solid black; background-color: rgba(23, 22, 22, 0.84); color: white; border-radius: 6px;">
        <header style="background-color: aliceblue; color: black;">
          <h1>  <b>
                <center>Resturant Manu Card</center>
            </b></h1>
        </header>
        <div class="box" style="display: flex; flex-direction: row; margin: auto;margin:10px;">
            <div class="box1" style="margin-right: 10px; background-color: rgba(183, 136, 112, 0.63);border: 1px solid black; border-radius: 4px;">
                <h2><b>Starters</b></h2><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">EXCELLENT</label><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">GOOD</label><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">AVERAGE</label><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">POOR</label>
            </div>
            <div class="box2">
                 <h2><b>FOODS</b></h2><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">paneer butter masala</label><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">veg bariyani</label><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">ice cream</label><br>
                <input type="checkbox" id="checkbox" name="0">
                <label for="">gullab jammun</label>
            </div>
        </div>
        <div class="box_sug" style="margin-left: 10px; margin-right:10px;background-color:  rgb(221, 217, 212);  border: 1px solid black; border-radius: 5px;">
            <h1 style="color: black;"><b>SUGGESTION</b></h1>
            <textarea name="#" id="#" placeholder="Enter your suggestion"></textarea><br>
            <button value="submit">SUBMIT</button>
        </div>
    </div>
</body>
</html>

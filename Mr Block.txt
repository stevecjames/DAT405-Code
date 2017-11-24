

//DAT405 / GAD405
//Little man drawing

//Initialization function
function setup() {
  //Size of window
  createCanvas(800, 600);


  //Size of surround
  strokeWeight(5);

  //No stroke for shapes
  noStroke();
}

//Rendering function
function draw() {
  //Background colour to light grey
  background(225);

  //Colour of man's body
  fill(255, 192, 203);

//Mr Block text
  textSize(36);
  textAlign(RIGHT);
  text("Mr Block :", 190, 100);

//head
  ellipse(400, 100, 100, 100);

  stroke(0, 64, 127);

//Neck
  line(400, 150, 400, height-440);

// Left eye
    ellipse(380, 90, 10, 10);

// Right eye
    ellipse(420, 90, 10, 10);

// mouth
  ellipse(400, 120, 10, 10);

// Pen
    line(270, 350, 380, height-410);

//Left hand
  ellipse(295, 320, 30, 30);

//Right hand
  ellipse(507, 320, 30, 30);

//Colour of man's suit
  fill(204, 102, 0);

//Body
  rect(320, 165, 160, 160);
//Left arm
  rect(280, 165, 30, 140);
//Right arm
  rect(490, 165, 30, 140);
//Left leg
  rect(340, 330, 40, 180);
//Right leg
  rect(420, 330, 40, 180);
  //Colour of shoes
  fill(0, 0, 0);
//Left shoe
  rect(300, 470, 40, 40);
  //Right shoe
  rect(460, 470, 40, 40);

}

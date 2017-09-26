document.getElementById('BtnDonate').addEventListener('click', function(){
  //Code in here executes when the user clicks the "Donate" button.
});

document.getElementById('BtnChurchill').addEventListener('click', function(){
  //Code in here executes when the user clicks the "Churchill" button.
});

document.getElementById('BtnGhandi').addEventListener('click', function(){
  //Code in here executes when the user clicks the "Ghandi" button.
});

document.getElementById('BtnDemosthenes').addEventListener('click', function(){
  //Code in here executes when the user clicks the "Demosthenes" button.
});

// speech objects

var churchillSpeech = {
    name: 'Winston Churchill',
    year: 1940,
    bce: false
};

var ghandiSpeech = {
    name: 'Ghandi',
    year: 1942,
    bce: false
};

var demosthenesSpeech = {
    name: 'Demosthenes',
    year: 342,
    bce: true
};

// array of speeches

var allSpeeches = ['churchillSpeech', 'ghandiSpeech', 'demosthenesSpeech'];

// a variable that contains a calculation of the difference between the year of Ghandi's speech and the year of Churchill's speech.


// Once all your data is set up, write console log statement (that executes when the page loads) that displays the following (with x being the value you calculated previously):
// Ghandi's speech and Churchill's speech are [x] years apart.

var difference =  ghandiSpeech.year - churchillSpeech.year;

difference = function() {
  console.log("Ghandi's speech and Churchill's speech are" + difference + " years apart");
};

// Then, when the user clicks the "Donate" button, make the console display how many speeches are in the array like this:
 

// There are [x] speeches on the page.

allSpeeches = function() {
  console.log("There are" + allSpeeches + "speeches on the page.");
};

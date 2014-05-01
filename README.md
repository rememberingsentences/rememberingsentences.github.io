RememberingSentences.github.io
==============================
<html><body>

<form id="form" action="https://docs.google.com/forms/d/1hMIa1eWAsWmNKNUJ9zXOxFT1DfqGKZn3yMd9nz_wW5U/formResponse" method="POST"></form>

<div id="page">
  <h1>Welcome!</h1>
  <div class="instructions" id="instructions">
    <p>INFORMED CONSENT: xxxxxxxxx </p><p>

INSTRUCTIONS:
In this exercise, you will hear a series of recorded sentences, played one at a time. After each one, your job is to type out as much as you can remember of the sentence.</p><p>

Make sure your volume is turned up before you begin.  If you don't hear the audio after you click 'Begin,' try opening the page in a different web browser. </p><p>

Click on 'Begin' to begin playing a sentence. You will hear it once, and then once more after a five second interval. Try to remember it (but do not take notes!).  Quickly click to go to the next screen and begin typing. (If you don't click within 5 seconds, the next screen will appear automatically.) </p><p>

Type as much of the sentence as you can remember; leave gaps where necessary. When you're sure you've done the best you can, you may click 'Next' ONCE to hear the next sentence.</p><p>

These sentences are intended to be difficult, and some of them are spoken in a strange way. So don't worry if you miss some words. Nobody performs at 100 percent on this task!  All we ask is that you try to remember as much as possible. If you do, you will get full AMT credit for performing the task regardless of your actual recall score.</p><p>
 
There are 58 sentences in total. The whole task will take about 45(?)minutes.</p><p>

First, please enter your Amazon Mechanical Turk ID. Please make sure it is correct or we will not be able to compensate you:
</p><p>
<label>AMT ID:</label><input type='text' id='AMTid'></p><p>


Ready? 

  </p>
  <button class="instructions" id="ready">Begin</button>
  </div>


</div>

<script src="jquery.2.1.0.js"></script>

<script>

var prefix = "http://s3.amazonaws.com/center_embedded_sentences/"
sources = [ {"audioSource": prefix+"1_Nora_Filler_1_reporter.wav",    "name": "entry.1797156307"}
           ,{"audioSource": prefix+"2_Nora_Filler_2_Peter.wav",       "name": "entry.781356652"}
           ,{"audioSource": prefix+"3_Nora_Filler_3A_Pilot.wav",      "name": "entry.2081559175"}
           ,{"audioSource": prefix+"4_Nora_Filler_4_concert.wav",     "name": "entry.1465695522"}
           ,{"audioSource": prefix+"5_Nora_Filler_5A_markets.wav",    "name": "entry.1572050354"}
           ,{"audioSource": prefix+"6_Nora_Filler_6_Bennie.wav",      "name": "entry.1772113026"}
           ,{"audioSource": prefix+"7_Nora_apples_ENC.wav",           "name": "entry.1271352997"}
           ,{"audioSource": prefix+"8_Nora_Filler_7_manuscript.wav",  "name": "entry.1303848164"}
           ,{"audioSource": prefix+"9_Nora_Filler_8_Fran.wav",        "name": "entry.1936261050"}
           ,{"audioSource": prefix+"10_Nora_cop_NPDisc.wav",          "name": "entry.1737735266"}
           ,{"audioSource": prefix+"11_Nora_Filler_9_monkey.wav",     "name": "entry.1409456649"}
           ,{"audioSource": prefix+"12_Nora_Filler_10_scouts.wav",    "name": "entry.763299335"}
           ,{"audioSource": prefix+"13_Nora_icecream_VP_DISC_2.wav",  "name": "entry.907169968"}
           ,{"audioSource": prefix+"14_Nora_Filler_11A_lions.wav",    "name": "entry.338608066"}
           ,{"audioSource": prefix+"15_Nora_fitness_ENC.wav",         "name": "entry.419430108"}
           ,{"audioSource": prefix+"16_Nora_Filler_12_meltdown.wav",  "name": "entry.1519950506"}
           ,{"audioSource": prefix+"17_Nora_Filler_13A_tests.wav",    "name": "entry.1857044394"}
           ,{"audioSource": prefix+"18_Nora_cat_NP_DISC.wav",         "name": "entry.1065654073"}
           ,{"audioSource": prefix+"19_Nora_Filler_14_chairman.wav",  "name": "entry.1084051716"}
           ,{"audioSource": prefix+"20_Nora_Filler_15_telescope.wav", "name": "entry.117463539"}
           ,{"audioSource": prefix+"21_Nora_poets2_VP_DISC_2.wav",    "name": "entry.1507046308"}
           ,{"audioSource": prefix+"22_Nora_Filler_16A_sprint.wav",   "name": "entry.1358173999"}
           ,{"audioSource": prefix+"23_Nora_Filler_17_reality.wav",   "name": "entry.911221271"}
           ,{"audioSource": prefix+"24_Nora_dish_ENC.wav",            "name": "entry.2023078511"}
           ,{"audioSource": prefix+"25_Nora_Filler_18A_bridge.wav",   "name": "entry.959136707"}
           ,{"audioSource": prefix+"26_Nora_tea_NPDisc.wav",          "name": "entry.506659438"}
           ,{"audioSource": prefix+"27_Nora_Filler_19_carpenter.wav", "name": "entry.455336529"}
           ,{"audioSource": prefix+"28_Nora_Filler_20_nanny.wav",     "name": "entry.764214279"}
           ,{"audioSource": prefix+"29_Nora_Filler_21_birthday.wav",  "name": "entry.1391488432"}
           ,{"audioSource": prefix+"30_Nora_gloves_VP_DISC_2.wav",    "name": "entry.840871287"}
           ,{"audioSource": prefix+"31_Nora_Filler_22A_bathtub.wav",  "name": "entry.2068797846"}
           ,{"audioSource": prefix+"32_Nora_Filler_23_umbrella.wav",  "name": "entry.1056931940"}
           ,{"audioSource": prefix+"33_Nora_game_ENC.wav",            "name": "entry.948320674"}
           ,{"audioSource": prefix+"34_Nora_Filler_24_professor.wav", "name": "entry.2060716011"}
           ,{"audioSource": prefix+"35_Nora_Filler_25_carlos.wav",    "name": "entry.2087940948"}
           ,{"audioSource": prefix+"36_Nora_ranger_NPDisc.wav",       "name": "entry.485583650"}
           ,{"audioSource": prefix+"37_Nora_Filler_26_Potter.wav",    "name": "entry.731248607"}
           ,{"audioSource": prefix+"38_Nora_mailbox_VP_DISC_2.wav",   "name": "entry.580886805"}
           ,{"audioSource": prefix+"39_Nora_Filler_27A_barbara.wav",  "name": "entry.1593135691"}
           ,{"audioSource": prefix+"40_Nora_Filler_28_artist.wav",    "name": "entry.23884217"}
           ,{"audioSource": prefix+"41_Nora_flight_ENC.wav",          "name": "entry.1561778615"}
           ,{"audioSource": prefix+"42_Nora_Filler_30_piggybank.wav", "name": "entry.1482902977"}
           ,{"audioSource": prefix+"43_Nora_Filler_38_seniorHome.wav","name": "entry.1998768659"}
           ,{"audioSource": prefix+"44_Nora_kids_NP_DISC.wav",        "name": "entry.1377899956"}
           ,{"audioSource": prefix+"45_Nora_Filler_31_chamomile.wav", "name": "entry.837546918"}
           ,{"audioSource": prefix+"46_Nora_Filler_34_poodle.wav",    "name": "entry.1523142405"}
           ,{"audioSource": prefix+"47_Nora_clinic_VP_DISC_2.wav",    "name": "entry.1708106695"}
           ,{"audioSource": prefix+"48_Nora_Filler_35A_bike.wav",     "name": "entry.1277233686"}
           ,{"audioSource": prefix+"49_Nora_Filler_36_seamstress.wav","name": "entry.1038758873"}
           ,{"audioSource": prefix+"50_Nora_condo_ENC.wav",           "name": "entry.1889592174"}
           ,{"audioSource": prefix+"51_Nora_Filler_37_viewers.wav",   "name": "entry.1900699696"}
           ,{"audioSource": prefix+"52_Nora_Filler_29_ransom.wav",    "name": "entry.1803191661"}
           ,{"audioSource": prefix+"53_Nora_pipes_NPDisc.wav",        "name": "entry.1566339712"}
           ,{"audioSource": prefix+"54_Nora_Filler_39_teenagers.wav", "name": "entry.879377898"}
           ,{"audioSource": prefix+"55_Nora_Filler_40_interview.wav", "name": "entry.175359123"}
           ,{"audioSource": prefix+"56_Nora_widow_VP_DISC_2.wav",     "name": "entry.320643011"}
           ,{"audioSource": prefix+"57_Nora_Filler_41_explorers.wav", "name": "entry.747791439"}
           ,{"audioSource": prefix+"58_Nora_Filler_42_closet.wav",    "name": "entry.1911648434"}
          ];
  
  var AMTidField = "<input type='hidden' value='' name='entry.1153672825"
  $("form").append(AMTidField);
  

for(i = 0; i<sources.length; i++){
  var name = sources[i]["name"]
  var input_string = "<input type='hidden' value='' name='"+name+"'>"
  $("#form").append(input_string);
}



var timer;
var masterIndex = 0;


play = function(){
  $("#page").html(audiohtml);
}

setToAudio = function() {
  setTimeout(function() {
  audioSource = sources[masterIndex]["audioSource"];
  audiohtml = "<audio src='"+audioSource+"' autoplay id='sound'></audio><button id='done'>Ready to type!</button>";

  play();

  timer = setTimeout(setToInput, 20000);
  $("#done").on("click", function(){
    clearTimeout(timer);
    setToInput();
  });

  }, 1000);

  
}

setToInput = function(inputname) {
    formhtml = "<label>Type as much as you can remember of the sentence.</label><input type='text' id='response'><button id='next'>Next</button>";
    $("#page").html(formhtml);
    console.log("called setToInput");
    
    record = function() {
      name = sources[masterIndex]["name"];
        response = $("#response").val();
        hidden_input = $("input[name='"+name+"']");
        hidden_input.val(response);
        masterIndex+=1;
        setToAudio();
        console.log(masterIndex);

    }
    record_final = function() {
        name = sources[masterIndex]["name"];
        response = $("#response").val();
        hidden_input = $("input[name='"+name+"']");
        hidden_input.val(response);
        console.log(masterIndex);
        $("#form").submit();
      }
    
      if(masterIndex<57) {
        recordtimer = setTimeout(function() { record(); }, 120000);
        $("#next").on("click", function(){
          clearTimeout(recordtimer);
          record();
          })};
        
      if(masterIndex == 57) {
          formhtml = "<label>Type as much as you can remember of the sentence.</label><input type='text' id='response'><button id='next'>Task complete!</button>";
          $("#page").html(formhtml);
          recordtimer = setTimeout(function() { record_final(); }, 120000);
          $("#next").on("click", function(){
          clearTimeout(recordtimer);
          record_final();
          })};

}


$("#ready").on("click", function(){AMTid = $("#AMTid").val();
  hidden_ID = $("input[name='entry.1153672825']");
  console.log(hidden_ID);
  hidden_ID.val(AMTid);
  console.log(AMTid);
  setToAudio();


});

</script>
</body>
</html>


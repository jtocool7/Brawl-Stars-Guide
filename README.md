<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <title>Brawl Stars Guide</title>
    <style>
      * {
        user-select: none;
        margin: 25;
        padding: 25;
      }

      body {


        align-items: center;

        background: url("https://www.techgamingreport.com/wp-content/uploads/2020/07/1594115971_962_THE-SUMMER-OF-MONSTERS-Brawl-Stars-UP.jpg");

      }

      #welcome {
        text-align: center;
        font-size: 2em;
        color: white;

      }

      #geist {
        border-radius: 50px;
        position: absolute;
        top: 300px;
        height: 50px;
        width: 100px;
        border: none;
        left: 350px;

      }



      #back {
        border-radius: 50px;
        position: absolute;
        top: 500px;
        height: 50px;
        width: 100px;
        border: none;
        left: 350px;
      }

      .hide {
        display: none;
      }

      .brawlers {
        display: grid;
        grid-template-columns: repeat(7, 2fr);
        grid-template-rows: repeat(7, 2fr);
        height: 700px;
        margin: 10px 0 25px;
        width: 700px;
        cursor: pointer;

        font-size: 25px;

      }


      #shelly:hover {
        color: #f0f0f0;
      }

      #nita:hover {
        color: #f0f0f0;
      }

      #colt:hover {
        color: #f0f0f0;
      }

      #bull:hover {
        color: #f0f0f0;
      }

      #jessie:hover {
        color: #f0f0f0;
      }

      #brock:hover {
        color: #f0f0f0;
      }

      #dynamike:hover {
        color: #f0f0f0;
      }

      #bo:hover {
        color: #f0f0f0;
      }

      #tick:hover {
        color: #f0f0f0;
      }

      #bit:hover {
        color: #f0f0f0;
      }

      #emz:hover {
        color: #f0f0f0;
      }

      #elprimo:hover {
        color: #f0f0f0;
      }

      #barley:hover {
        color: #f0f0f0;
      }

      #poco:hover {
        color: #f0f0f0;
      }

      #rosa:hover {
        color: #f0f0f0;
      }

      #rico:hover {
        color: #f0f0f0;
      }

      #darryl:hover {
        color: #f0f0f0;
      }

      #penny:hover {
        color: #f0f0f0;
      }

      #carl:hover {
        color: #f0f0f0;
      }



      #jacky:hover {
        color: #f0f0f0;
      }

      #piper:hover {
        color: #f0f0f0;
      }

      #pam:hover {
        color: #f0f0f0;
      }

      #frank:hover {
        color: #f0f0f0;
      }

      #bibi:hover {
        color: #f0f0f0;
      }

      #bea:hover {
        color: #f0f0f0;
      }

      #nani:hover {
        color: #f0f0f0;
      }

      #mortis:hover {
        color: #f0f0f0;
      }

      #tara:hover {
        color: #f0f0f0;
      }

      #mr-p:hover {
        color: #f0f0f0;
      }

      #sprout:hover {
        color: #f0f0f0;
      }

      #gene:hover {
        color: #f0f0f0;
      }

      #max:hover {
        color: #f0f0f0;
      }



      #spike:hover {
        color: #f0f0f0;
      }

      #crow:hover {
        color: #f0f0f0;
      }

      #leon:hover {
        color: #f0f0f0;
      }

      #sandy:hover {
        color: #f0f0f0;
      }

      #gale:hover {
        color: #f0f0f0;
      }

      #surge:hover {
        color: #f0f0f0;
      }

      #a {
        position: absolute;
        top: 50px;
      }
      
      #cc{
         position: absolute;
        top: 50px;
      }

      #b {
        position: absolute;
        top: 50px;
      }

      #c {
        position: absolute;
        top: 50px;
      }
      
      #s{
         position: absolute;
        top: 50px;
      }

      #d {
        position: absolute;
        top: 50px;
      }

      #e {
        position: absolute;
        top: 50px;
      }
      
      #dd{
         position: absolute;
        top: 50px;
      }

      #f {
        position: absolute;
        top: 50px;
      }
      
      #aa{
         position: absolute;
        top: 50px;
        width:400px;
      }

      #g {
        position: absolute;
        top: 50px;
      }

      #i {
        position: absolute;
        top: 50px;
      }

      #j {
        position: absolute;
        top: 50px;
      }

      #k {
        position: absolute;
        top: 50px;
      }

      #l {
        position: absolute;
        top: 50px;
      }

      #m {
        position: absolute;
        top: 50px;
      }
      
      #w{
       position: absolute;
        top: 50px; 
      }

      #n {
        position: absolute;
        top: 50px;
      }

      #o {
        position: absolute;
        top: 50px;
      }

      #p {
        position: absolute;
        top: 50px;
      }
      
      #t{
         position: absolute;
        top: 50px;
      }

      #q {
        position: absolute;
        top: 50px;
      }

      #r {
        position: absolute;
        top: 50px;
      }
      
      #ff{
        position: absolute;
        top: 50px;
      }
      
      #ee{
         position: absolute;
        top: 50px;
      }
      
      #u{
        position: absolute;
        top: 50px; 
      }
      
      #v{
        position: absolute;
        top: 50px; 
      }
      
      #bb{
       position: absolute;
        top: 50px;  
      }
      
      #x{
         position: absolute;
        top: 50px; 
      }
      
      #y{
         position: absolute;
        top: 50px; 
      }
      
     #z{
       position: absolute;
        top: 50px; 
     }
     
     

      #shell {
       color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #nit {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #leo {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #surg {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #col {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #bulll {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #bi {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #em {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #nan {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;

      }
      
      #jess{
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;

      }

      #gal {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #spi {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
      }

      #ma {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }

      #bob {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }

      #qbit {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #bro{
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #darrl{
          color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #barl{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }

      #po {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #pipe{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }

      #jack {
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
     #cro{
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
     }
     
     #pen{
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
     }
     
     #boo{
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
     }
     
     #ros{
       color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
     }
     
     #car{
        color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
     }
      
      #primo{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #mite{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #pa{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #ti{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }
      
      #ric{
         color: #f0f0f0;
        position: absolute;
        top: 50px;
        left: 450px;
        font-size: 25px;
        color: #f0f0f0;
      }


      #fall {
        border-radius: 50px;
        position: absolute;
        top: 500px;
        height: 50px;
        width: 100px;
        border: none;
        left: 350px;
      }

    </style>
  </head>

  <body>



    <p id="welcome">
      Welcome to The Brawl Stars Guide
      <button id="geist" onclick="myFunctionA()">
        Next

      </button>


    </p>

    <button id="back" class="hide" onclick="myFunctionB()">
      Back
    </button>


    <button id="fall" class="hide" onclick="myFunctionC()">
      Back
    </button>

    <div class="brawlers">
      <div id="shelly" class="hide" onclick="myFunction()">
        Shelly
      </div>
      <div id="nita" class="hide" onclick="bruce()">
        Nita
      </div>
      <div id="colt" class=hide onclick="storm()">
        Colt
      </div>


      <div id="bull" class="hide" onclick="dozer()">
        Bull
      </div>


      <div id="jessie" class="hide" onclick="scrapy()">
        Jessie
      </div>


      <div id="brock" class="hide" onclick="party()">
        Brock
      </div>


      <div id="dynamike" class="hide" onclick="dyno()">
        Dynamike
      </div>


      <div id="bo" class=hide onclick="mine()">
        Bo
      </div>


      <div id="tick" class="hide" onclick="tnt()">
        Tick
      </div>

      <div id="bit" class="hide" onclick="arcade()">
        8-Bit
      </div>

      <div id="emz" class="hide" onclick="hair()">
        Emz
      </div>
      <div id="elprimo" class="hide" onclick="punch()">
        El Primo
      </div>
      <div id="barley" class="hide" onclick="bot()">
        Barley
      </div>
      <div id="poco" class="hide" onclick="gutar()">
        Poco
      </div>
      <div id="rosa" class="hide" onclick="flower()">
        Rosa
      </div>
      <div id="rico" class="hide" onclick="bounce()">
        Rico
      </div>
      <div id="darryl" class="hide" onclick="roll()">
        Darryl
      </div>
      <div id="penny" class="hide" onclick="bomb()">
        Penny
      </div>
      <div id="carl" class="hide" onclick="pick()">
        Carl
      </div>
      <div id="jacky" class="hide" onclick="drill()">
        Jacky
      </div>
      <div id="piper" class="hide" onclick="sniper()">
        Piper
      </div>
      <div id="pam" class="hide" onclick="mama()">
        Pam
      </div>
      <div id="frank" class="hide">
        Frank
      </div>
      <div id="bibi" class="hide" onclick="bat()">
        Bibi
      </div>
      <div id="bea" class="hide">
        Bea
      </div>
      <div id="nani" class="hide" onclick="peep()">
        Nani
      </div>
      <divi id="mortis" class="hide">Mortis</divi>
      <div id="tara" class="hide">
        Tara
      </div>
      <div id="mr-p" class="hide">
        Mr.P
      </div>
      <div id="sprout" class="hide">
        Sprout
      </div>
      <div id="gene" class="hide" onclick="hand()">
        Gene
      </div>
      <div id="max" class="hide" onclick="fast()">
        Max
      </div>
      <div id="spike" class="hide" onclick="cacti()">
        Spike
      </div>
      <div id="crow" class="hide" onclick="jump()">
        Crow
      </div>
      <div id="leon" class="hide" onclick="invis()">
        Leon
      </div>
      <div id="sandy" class="hide">
        Sandy
      </div>
      <div id="gale" class="hide" onclick="snow()">
        Gale
      </div>
      <div id="surge" class="hide" onclick="boom()">
        Surge
      </div>
    </div>
    <div class="moves">


    </div>
<audio src="https://vignette.wikia.nocookie.net/brawlstars/images/3/3a/Shelly_start_01.ogg/revision/latest?cb=20190803143405" id="one" class="hide" controls></audio>

<audio src="https://vignette.wikia.nocookie.net/brawlstars/images/9/9e/Nita_start_vo_01.ogg/revision/latest?cb=20190803151014" id="two" class="hide"></audio>
    <img id="a" class="hide" src="https://cdna.artstation.com/p/assets/images/images/016/220/398/large/supercell-art-screenshot004.jpg?1551359685" alt="picture of shelly in brawlstars" width="400px">
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/b/bd/Hotshot_start_01.ogg/revision/latest?cb=20190803154018" id="three" class="hide" controls></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/3/3d/Bull_start_vo_01.ogg/revision/latest?cb=20190804164929" id="four" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/1/17/8bit_start_vo_01.ogg/revision/latest?cb=20190919032301" id="five" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/c/c2/Emz_start_vo_01.ogg/revision/latest?cb=20191023212001" id="six" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/b/bd/Poco_start_01.ogg/revision/latest?cb=20190730050619" id="seven" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/d/d7/Darryl_start_vo_03.ogg/revision/latest?cb=20200513161940" id="eight" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/1/13/Jackie_die_vo_01.ogg/revision/latest?cb=20200318031655" class="hide" id="nine"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/5/5a/Bibi_start_vo_01.ogg/revision/latest?cb=20190802162234" id="ten" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/3/37/Nani_start_vo_01.ogg/revision/latest?cb=20200529162414" class="hide" id="eleven"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/0/00/Gene_vo_01.ogg/revision/latest?cb=20190801171308" id="twe" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/a/a1/Max_start_vo_01.ogg/revision/latest?cb=20191219042905" class="hide" id="thir"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/0/01/Leon_ulti_vo_02.ogg/revision/latest?cb=20191023203227" id="ft"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/6/6b/Gale_kill_vo_04.ogg/revision/latest?cb=20200513172326" class="hide" id="fit"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/b/ba/Surge_ulti_vo_01.ogg/revision/latest?cb=20200702171329" id="sixt" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/0/02/Jess_start_vo_02.ogg/revision/latest?cb=20190804171437" id="sevt"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/d/d7/Pam_start_vo_01.ogg/revision/latest?cb=20190802155054" id="eit" class="hide"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/4/48/Crow_kills_02.ogg/revision/latest?cb=20190731155547" class="hide" id="nitt"></audio>
    <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/c/c4/Brock_kill_vo_01.ogg/revision/latest?cb=20190804175004" id="twee"></audio>
  <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/9/90/Tnt_guy_start_vo_02.ogg/revision/latest?cb=20190805162405" id="pega" class="hide"></audio>
  <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/5/54/Bo_lead_vo_03.ogg/revision/latest?cb=20190805181213" id="elyse" class="hide"></audio>
  <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/3/31/Tick_vo_01v2.ogg/revision/latest?cb=20190805170515" class="hide" id="twoo"></audio>
  <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/c/cf/Barley_ulti_02.ogg/revision/latest?cb=20190730180210" class="hide" id="threee"></audio>
  <audio src="https://vignette.wikia.nocookie.net/brawlstars/images/0/0a/Rosa_start_03.ogg/revision/latest?cb=20190730154120" id="roo" class="hide"></audio>
  <audio  class="hide" id="noo" src="https://vignette.wikia.nocookie.net/brawlstars/images/6/6b/Rick_start_vo_01.ogg/revision/latest?cb=20190801162105"></audio>
  <audio class="hide" id="cook" src="https://vignette.wikia.nocookie.net/brawlstars/images/8/8e/Penny_lead_vo_02.ogg/revision/latest?cb=20190731192016"></audio>
  <audio  id="thro" class="hide" src="https://vignette.wikia.nocookie.net/brawlstars/images/1/1e/Carl_kill_vo_04.ogg/revision/latest?cb=20190731234259"></audio>
  <audio id="cereal" class="hide" src="https://vignette.wikia.nocookie.net/brawlstars/images/3/30/Piper_start_01.ogg/revision/latest?cb=20190802144843" controls></audio>

    <p id="shell" class="hide">
      Shelly's spread-fire shotgun blasts the other team with buckshot.<br>
      Her super destroys cover and keeps her opponents at a distance!
      </p>
    <img id="b" class="hide" src="https://cdna.artstation.com/p/assets/images/images/016/220/686/large/supercell-art-nita-logo.jpg?1551360610" alt="picture of nita in brawlstars" width="400px">
    <p id="nit" class="hide">
      Nita strikes her enemies with a thunderous shockwave.<br>
      Her super summons a massive bear to fight by her side!
    </p>
    <img id="c" class="hide" src="https://cdnb.artstation.com/p/assets/marmosets/images/023/618/733/medium/phillip-lockwood-mview-image20200123-18620-yfy1qa.jpg?1579791159" alt="picture of leon in brawl stars" width="400px">
    <p id="leo" class="hide">
      Leon shoots a quick salvo of blades at his target.<br>
      His super trick is a smoke bomb that makes him invisible for a while!
    </p>
    <img id="d" class="hide" src="https://imagekit.androidphoria.com/wp-content/uploads/Surge-el-nuevo-brawler-crom%C3%A1tico-de-Brawl-Stars.jpg" alt="picture of surge brawl stars" width=400px>
    <p id="surg" class="hide">
      He's a Protector with a penchant for parties.<br>Surge attacks foes with energy drink blasts that split in two on contact.<br>His super upgrades his stats in three stages and comes complete with totaly awesome body mods!
    </p>
    <img id="e" class="hide" src="https://cdnb.artstation.com/p/assets/images/images/016/220/045/large/supercell-art-colt-logo.jpg?1551358764" alt="picture of colt brawl stars" width=400>
    <p id="col" class="hide">
      Colt fires an acurate burst of bullets from from his dual revolvers.<br>
      His Super shreds cover and extends the bullet barrage!
    </p>
    <img id="f" class="hide" src="https://gamersantai.com/wp-content/uploads/2019/08/Bull-Brawl-Stars.png" alt="bull in brawl stars" width="400px">
    <p id="bulll" class="hide">
      Bull deals massive damage up close with his shotgun.<br>For his super move, he charges through barriers and knocks back enimies!
    </p>
    <img id="g" class="hide" src="https://i0.wp.com/gamerempire.net/wp-content/uploads/2019/05/Bibi-Brawl-Stars.png?resize=512%2C346&ssl=1" alt=" bibi in brawl stars" height="250px">
    <p id="bi" class="hide">
      Batter Up!<br>
      Bibi's got a sweet swing that can knock back enimies when her Home Run Bar is Charged.<br>Her Super is a bouncing ball of gum thet deals damage.
    </p>
    <img id="i" class="hide" src="https://cdna.artstation.com/p/assets/marmosets/images/023/618/832/medium/phillip-lockwood-mview-image20200123-18131-z3loft.jpg?1579791419" alt="emz in brawl stars" width=400px>
    <p id=em class="hide">
      Emz attacks with blasts of hair spray that deals damage over time,<br> and slows down opponents with her super.
    </p>
    <img id="j" class="hide" src="https://wonder-day.com/wp-content/uploads/2020/05/wonder-day-nani-2-1024x576.jpg" alt="nani in brawl stars" width="400">
    <p id="nan" class="hide">
      Nani love her friends and looks over them with a watchful lens.<br>
      She handles uthreats with angeled shots,<br>and her Super allows nani to commandeer her pal pep,<br>who goes out with a bang!
    </p>
    <img id="k" class="hide" src="https://cdnb.artstation.com/p/assets/marmosets/images/026/659/133/medium/phillip-lockwood-mview-image20200513-19367-1klnshe.jpg?1589373954" alt="picture of gale brawl stars" width="400px">
    <p id="gal" class="hide">
      Gale is a tireless handyman who gets no rest.<br>With his blower ,<br> he blasts foes with a wide shot of wind shot of wind and snow,<br>while his Super pushes them back with a forceful blizzard!
    </p>
    <img id="l" class="hide" src="https://cdna.artstation.com/p/assets/images/images/016/220/082/large/supercell-art-spike-logo.jpg?1551358916" alt="picture of spike brawl stars" width=400px>
    <p id="spi" class="hide">
      Spike throws cactus grenades that send needles flying,<br>and a show-stopping Super:a feild a feild of cactus spines that <br>slows down and damages enemies!
    </p>
    <img id="m" class="hide" src="https://cdnb.artstation.com/p/assets/images/images/026/563/479/large/giovanni-maisto-max-character-03.jpg?1589124055" alt=" max in brawl stars" width=400px>
    <p id="ma" class="hide">
      Max goes fast!<br> Her attack is a fast-firing blaster.<br> Her super speeds up her and allies!
    </p>
    <img id="n" class="hide" src="https://cdnb.artstation.com/p/assets/marmosets/images/016/219/823/medium/supercell-art-mview-image20190228-28586-1mj4fc.jpg?1551357962" alt="gene in brawl stars" width="400px">
    <p id="bob" class="hide">
      Gene uses his magic lamp to shoot a splitting projectile.<br>His super is a magical hand<br> that grabs and pulls enemies close!
    </p>
    <img id="o" class="hide" src="https://cdna.artstation.com/p/assets/marmosets/images/023/644/876/medium/phillip-lockwood-mview-image20200124-30561-2u4dv6.jpg?1579873217" alt="8-bit in brawl stars" width="400px">
    <p id="qbit" class="hide">
      8-bit lumbers along like an arcade cabinet on legs.<br>He shoots blaster brams and his super boosts<br>friendlies dmage!
    </p>
    <img id="p" class="hide" src="https://cdna.artstation.com/p/assets/marmosets/images/016/219/538/medium/supercell-art-mview-image20190228-5452-rmyc03.jpg?1551357274" alt="poco in brawl stars" width="400px">
    <p id="po" class="hide">
      Poco fires damaging sound waves at enemies.<br>His super can heal both poco himself and <br> his teammates!
    </p>
    <img id="q" class="hide" src="https://i.ytimg.com/vi/NFj9WKO8GzM/maxresdefault.jpg" alt=" jacky from brawl stars" width="400px">
    <p id="jack" class="hide">
      Jacky works her Jackhammer to shake up the ground<br> and nearby enemies.Her super pulls in nearby foes<br> leaving them in the dust!
    </p>
    <img id="r" class="hide" src="https://i.ytimg.com/vi/uXRkIuQyxzs/maxresdefault.jpg" alt="darryl in brawl stars " width="400px">
    <p id="darrl" class="hide">
    Darryl has a powerful double-shotgun attack.<br> His Super move is a reckless roll inside his bouncy barrel!
    </p>
    <img id="s" class="hide"src="https://static.wixstatic.com/media/31be3b_19f1a2b26f2f44ca9dd70b4e3f0f58b2~mv2.jpg/v1/fit/w_720,h_389,al_c,q_80/file.png" alt="pam brawl stars" width="400px">
    <p id="pa" class="hide">
    Pam shoots from the hip, peppering targets with shrapnel.<br> Her Super is a healing turret that restores her and teammates' health!
    </p>
   <audio id="el" class="hide" src="https://vignette.wikia.nocookie.net/brawlstars/images/e/e8/El_primo_start_vo_03.ogg/revision/latest?cb=20190730163306" controls></audio>
<img id="t" class="hide" src="https://i.ytimg.com/vi/-Zgkd2vVVnk/maxresdefault.jpg" alt="el primo in brawl stars" width="400px">
<p id="primo" class="hide">
El Primo throws a flurry of punches at his enemies.<br> His Super is a leaping elbow drop that deals damage to all caught underneath!
</p>
<img id="u" class="hide" src="https://cdn.boop.pl/uploads/2020/05/maxresdefault-7.jpg" alt="jessie brawl stars" width="400px">
<p id="jess" class="hide">
Jessie's Shock Rifle shoots energy orbs that bounce between enemies. Her Super deploys a cute but deadly gun turret!
</p>
<img id="v" src="https://image.jeuxvideo.com/medias-md/154707/1547068930-5152-artwork-tir-supercell-free-to-play.jpg" alt="crow in brawl stars" width="400px" class="hide">
<p id="cro" class="hide">
Crow fires a trio of poisoned daggers.<br> As a Super move he leaps, <br>firing daggers both on jump and on landing!
</p>
<img id="w" class="hide" src="https://i.redd.it/u5qtjfkl8h121.jpg" alt="brock in brawl stars" width="400px">
<p id="bro" class="hide">
Brock fires a long-range, explosive rocket at enemies. His Super is a ballistic rocket barrage that destroys cover!
</p>
<img class="hide" id="x" src="https://carboncostume.com/wordpress/wp-content/uploads/2020/06/dynamike-brawlstars.jpg" alt="dynamike in brawl stars" width="400px">
<p id="mite" class="hide">
Dynamike lobs two explosive sticks of dynamite. His Super attack is a whole barrel full of dynamite that blows up cover!
</p>
<img id="y" class="hide" src="https://www.appgemeinde.de/wp-content/uploads/Brawl-Stars-Bo-Beitragsbild-e1583846208838.png" alt="bo in brawl stars" width="400px">
<p id="boo" class="hide">
Bo fires three explosive arrows toward his targets. His Super ability places a trio of hidden, explosive mines on the ground!
</p>
<img id="z" class="hide" src="https://i.redd.it/txpkux7u95731.jpg" alt="tick in brawl stars" width=400px>
<p class="hide" id="ti">
Tick is a metal ball of barely controlled excitement and energy - explosive energy! He throws mines, and his Super makes his head detach, seek a target and explode.
</p>
<img class="hide" id="aa" src="https://i1.wp.com/gamerempire.net/wp-content/uploads/2019/03/Barley-Brawl-Stars.png?resize=512%2C346&ssl=1" alt="barley brawl stars">
<p  id="barl" class="hide">
Barley attacks by lobbing bottles at enemies, doing splash damage. His Super is a huge barrage of burning bottles!
</p>
<img class="hide" id="bb" src="https://assets.change.org/photos/3/kp/hg/BWKphGLWtQTrQzy-800x450-noPad.jpg?1556390542" alt=" rosa brawl stars " width="440px">
<p class="hide" id="ros">This boxing botanist will plant her feet and go toe to toe! Her Super gives her tough, vegan protective gear.</p>
<img id="cc" class="hide" src="https://static1.millenium.gg/entity_articles/0/24/0/@/23853-17400-brawl-stars-rico-orig-1-orig-1.png" alt=" rico in brawl stars" width="400px">
<p class="hide" id="ric">
Rico fires a burst of bullets that bounce off walls. His Super burst is a long barrage of bouncy bullets that pierce targets!
</p>
<img id="dd" class="hide" src="https://i.redd.it/f3toz58cyp121.png" alt="penny in brawl stars" width="400px">
<p class="hide" id="pen">
Penny shoots bags of coins, damaging the target and anyone standing behind. Her Super is a mortar-style cannon turret!
</p>
<img class="hide" id="ee" src="https://i.redd.it/hge4kzb5v4o21.png" alt=" carl in brawl stars" width="400px">
<p class="hide" id="car">
Carl throws his Pickaxe like a boomerang. His Super is a crazy cart spin that clobbers anyone around him.
</p>
<img id="ff" class="hide" src="https://i.ytimg.com/vi/0cOsLTM5l9c/hqdefault.jpg" alt="piper in brawl stars" height="275
px">
<p id="pipe" class="hide">
Piper's sniper shots do more damage the farther they travel. Her Super drops grenades at her feet, while Piper herself leaps away!
</p>
<img src="https://i0.wp.com/gamerempire.net/wp-content/uploads/2019/03/Frank-Brawl-Stars.png?resize=512%2C346&ssl=1" alt="frANK BRAWL STARS">
    <script>
      // barley poco rosa rico darryl penny carl jacky piper pam frank bibi  bea nani mortis tara mr.p sprout gene max sp ike crow leon sandy gale surge



      const shelly = document.getElementById("shelly");
      const colt = document.getElementById("colt");
      const nita = document.getElementById("nita");
      const bull = document.getElementById("bull");
      const jessie = document.getElementById("jessie");
      const brock = document.getElementById("brock");
      const dynamike = document.getElementById("dynamike");
      const bo = document.getElementById("bo");
      const tick = document.getElementById("tick");
      const bit = document.getElementById("bit");
      const emz = document.getElementById("emz");
      const elPrimo = document.getElementById("elprimo");
      const barley = document.getElementById("barley");
      const poco = document.getElementById("poco");
      const rosa = document.getElementById("rosa");
      const rico = document.getElementById("rico");
      const darryl = document.getElementById("darryl");
      const penny = document.getElementById("penny");
      const carl = document.getElementById("carl");
      const jacky = document.getElementById("jacky");
      const piper = document.getElementById("piper");
      const pam = document.getElementById("pam");
      const frank = document.getElementById("frank");
      const bibi = document.getElementById("bibi");
      const bea = document.getElementById("bea");
      const nani = document.getElementById("nani");
      const mortis = document.getElementById("mortis");
      const tara = document.getElementById("tara");
      const mrp = document.getElementById("mr-p");
      const sprout = document.getElementById("sprout");
      const gene = document.getElementById("gene");
      const max = document.getElementById("max");
      const spike = document.getElementById("spike");
      const crow = document.getElementById("crow");
      const leon = document.getElementById("leon");
      const sandy = document.getElementById("sandy");
      const gale = document.getElementById("gale");
      const surge = document.getElementById("surge");
      const back = document.getElementById("back");
      const shell = document.getElementById("shell");
      const a = document.getElementById("a");
      const button = document.getElementById('geist');
      const title = document.getElementById("welcome");
      const fall = document.getElementById("fall");
      const b = document.getElementById("b");
      const nit = document.getElementById("nit");
      const c = document.getElementById("c");
      const leo = document.getElementById("leo");
      const d = document.getElementById("d");
      const surg = document.getElementById("surg");
      const col = document.getElementById("col");
      const e = document.getElementById("e");
      const f = document.getElementById("f");
      const bul = document.getElementById("bulll");
      const em = document.getElementById("em");
      const i = document.getElementById("i");
      const j = document.getElementById("j");
      const nan = document.getElementById("nan");
      const k = document.getElementById("k");
      const l = document.getElementById("l");
      const spi = document.getElementById("spi");
      const m = document.getElementById("m");
      const ma = document.getElementById("ma");
      // the open button
      function myFunctionA() {





        button.style.display = "none";
        title.style.display = "none";
        shelly.classList.remove('hide');
        nita.classList.remove('hide');
        colt.classList.remove('hide');
        bull.classList.remove('hide');
        jessie.classList.remove('hide');
        brock.classList.remove('hide');
        dynamike.classList.remove('hide');
        bo.classList.remove('hide');
        tick.classList.remove('hide');
        bit.classList.remove('hide');
        emz.classList.remove('hide');
        elPrimo.classList.remove('hide');
        barley.classList.remove('hide');
        poco.classList.remove('hide');
        rosa.classList.remove('hide');
        rico.classList.remove('hide');
        darryl.classList.remove('hide');
        penny.classList.remove('hide');
        carl.classList.remove('hide');
        jacky.classList.remove('hide');
        piper.classList.remove('hide');
        pam.classList.remove('hide');
        frank.classList.remove('hide');
        bibi.classList.remove('hide');
        bea.classList.remove('hide');
        nani.classList.remove('hide');
        mortis.classList.remove('hide');
        mrp.classList.remove('hide');
        sprout.classList.remove('hide');
        gene.classList.remove('hide');
        max.classList.remove('hide');
        spike.classList.remove('hide');
        crow.classList.remove('hide');
        leon.classList.remove('hide');
        sandy.classList.remove('hide');
        gale.classList.remove('hide');
        surge.classList.remove('hide');
        fall.classList.remove('hide');
      }


      // barley poco rosa rico darryl penny carl jacky piper pam frank bibi  bea nani mortis tara mr.p sprout gene max spike crow leon sandy gale surge




      // shelly
      function myFunction() {

        a.classList.remove('hide');

        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        back.classList.remove('hide');
        shell.classList.remove('hide');
        fall.classList.add('hide');
        one.play();
      }


      // 1st back button
      function myFunctionB() {
        a.classList.add('hide');
        shelly.classList.remove('hide');
        nita.classList.remove('hide');
        colt.classList.remove('hide');
        bull.classList.remove('hide');
        jessie.classList.remove('hide');
        brock.classList.remove('hide');
        dynamike.classList.remove('hide');
        bo.classList.remove('hide');
        tick.classList.remove('hide');
        bit.classList.remove('hide');
        emz.classList.remove('hide');
        elPrimo.classList.remove('hide');
        barley.classList.remove('hide');
        poco.classList.remove('hide');
        rosa.classList.remove('hide');
        rico.classList.remove('hide');
        darryl.classList.remove('hide');
        penny.classList.remove('hide');
        carl.classList.remove('hide');
        jacky.classList.remove('hide');
        piper.classList.remove('hide');
        pam.classList.remove('hide');
        frank.classList.remove('hide');
        bibi.classList.remove('hide');
        bea.classList.remove('hide');
        nani.classList.remove('hide');
        mortis.classList.remove('hide');
        mrp.classList.remove('hide');
        sprout.classList.remove('hide');
        gene.classList.remove('hide');
        max.classList.remove('hide');
        spike.classList.remove('hide');
        crow.classList.remove('hide');
        leon.classList.remove('hide');
        sandy.classList.remove('hide');
        gale.classList.remove('hide');
        surge.classList.remove('hide');
        shell.classList.add('hide');
        back.classList.add('hide');
        fall.classList.remove('hide');
        b.classList.add('hide');
        nit.classList.add('hide');
        c.classList.add('hide');
        leo.classList.add('hide');
        surg.classList.add('hide');
        d.classList.add('hide');
        col.classList.add('hide');
        e.classList.add('hide');
        f.classList.add('hide');
        bul.classList.add('hide');
        bi.classList.add('hide');
        g.classList.add('hide');
        i.classList.add('hide');
        em.classList.add('hide');
        j.classList.add("hide");
        nan.classList.add("hide");
        gal.classList.add("hide");
        k.classList.add('hide');
        l.classList.add('hide');
        spi.classList.add('hide');
        ma.classList.add('hide');
        m.classList.add('hide');
        n.classList.add('hide');
        bob.classList.add('hide');
        o.classList.add('hide');
        qbit.classList.add('hide');
        po.classList.add('hide');
        p.classList.add('hide');
        q.classList.add('hide');
        jack.classList.add('hide');
        r.classList.add('hide');
        darrl.classList.add('hide');
        t.classList.add('hide');
        primo.classList.add('hide');
        u.classList.add('hide');
        jess.classList.add('hide');
        s.classList.add('hide');
        pa.classList.add('hide');
        cro.classList.add('hide');
        v.classList.add('hide');
         w.classList.add('hide');
        bro.classList.add('hide');
        x.classList.add('hide');
        mite.classList.add('hide');
        y.classList.add('hide');
        boo.classList.add('hide');
        ti.classList.add('hide');
        z.classList.add('hide');
        aa.classList.add('hide');
        barl.classList.add('hide');
        ros.classList.add('hide');
        bb.classList.add('hide')
        ric.classList.add('hide');
        cc.classList.add('hide');
        dd.classList.add('hide');
        pen.classList.add('hide');
        ee.classList.add('hide');
        car.classList.add('hide');
        ff.classList.add('hide');
        pipe.classList.add('hide');
        
      };
      // second back button
      function myFunctionC() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        title.style.display = "block";
        button.style.display = "block";

      }

      // nita 
      function bruce() {
        b.classList.remove('hide');
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        back.classList.remove('hide');
        nit.classList.remove('hide');
        fall.classList.add('hide');
        two.play();
      }
      // leon
      function invis() {
        c.classList.remove('hide');
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        back.classList.remove('hide');
        fall.classList.add('hide');
        leo.classList.remove('hide');
        ft.play();
      }

      // surge
      function boom() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        back.classList.remove('hide');
        fall.classList.add('hide');
        d.classList.remove('hide');
        surg.classList.remove('hide');
        sixt.play();
      }

      // colt
      function storm() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        col.classList.remove('hide');
        e.classList.remove('hide');
        three.play();
        
      }
      // bull
      function dozer() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        f.classList.remove('hide');
        bul.classList.remove('hide');
        four.play();
      }

      function bat() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        g.classList.remove('hide');
        bi.classList.remove('hide');
        ten.play();
      }


      function hair() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        i.classList.remove('hide');
        em.classList.remove('hide');
six.play();
      }

      function peep() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        j.classList.remove("hide");
        nan.classList.remove("hide");
        eleven.play();
      }

      function snow() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        k.classList.remove('hide');
        gal.classList.remove('hide');
        fit.play();
      }

      function cacti() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        l.classList.remove('hide');
        spi.classList.remove('hide');
      }

      function fast() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        m.classList.remove('hide');
        ma.classList.remove('hide');
        thir.play();
      }

      function hand() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        bob.classList.remove('hide');
        n.classList.remove('hide');
        twe.play();
      }

      function arcade() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        o.classList.remove('hide');
        qbit.classList.remove('hide');
        five.play();
      }

      function gutar() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        po.classList.remove('hide');
        p.classList.remove('hide');
        seven.play();
      }

      function drill() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        q.classList.remove('hide');
        jack.classList.remove('hide');
        nine.play();
      }

      function roll() {
        shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        r.classList.remove("hide");
        darrl.classList.remove('hide');
        eight.play();
        
      }
      
      function punch(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        el.play();
        t.classList.remove('hide');
        primo.classList.remove('hide');
        
      }
      
      function scrapy(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        u.classList.remove('hide');
        jess.classList.remove('hide');
        sevt.play();
      }
      
      function mama(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        pa.classList.remove('hide');
        s.classList.remove('hide');
        eit.play();
      }
      
      function jump(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        v.classList.remove('hide');
        cro.classList.remove('hide');
        nitt.play();
      }
      
      function party(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        w.classList.remove('hide');
        bro.classList.remove('hide');
        twee.play();
      }
      
      function dyno(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        x.classList.remove('hide');
        mite.classList.remove('hide');
      pega.play();
      }
      
      function mine(){
       shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        elyse.play();
        y.classList.remove('hide');
        boo.classList.remove('hide');
      }
      
      function tnt(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        z.classList.remove('hide');
        ti.classList.remove('hide');
        twoo.play();
      }
      
      function bot(){
       shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        aa.classList.remove('hide');
        threee.play();
        barl.classList.remove('hide');
      }
      
      function flower(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        bb.classList.remove('hide');
        ros.classList.remove('hide');
        roo.play();
      }
      
      function bounce(){
       shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        noo.play();
        cc.classList.remove('hide');
        ric.classList.remove('hide');
      }
      
      function bomb(){
       shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        dd.classList.remove('hide');
        pen.classList.remove('hide');
        cook.play();
      }
      
      function pick(){
      shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        car.classList.remove('hide');
        ee.classList.remove('hide');
        thro.play();
      }
      
      function sniper(){
       shelly.classList.add('hide');
        nita.classList.add('hide');
        colt.classList.add('hide');
        bull.classList.add('hide');
        jessie.classList.add('hide');
        brock.classList.add('hide');
        dynamike.classList.add('hide');
        bo.classList.add('hide');
        tick.classList.add('hide');
        bit.classList.add('hide');
        emz.classList.add('hide');
        elPrimo.classList.add('hide');
        barley.classList.add('hide');
        poco.classList.add('hide');
        rosa.classList.add('hide');
        rico.classList.add('hide');
        darryl.classList.add('hide');
        penny.classList.add('hide');
        carl.classList.add('hide');
        jacky.classList.add('hide');
        piper.classList.add('hide');
        pam.classList.add('hide');
        frank.classList.add('hide');
        bibi.classList.add('hide');
        bea.classList.add('hide');
        nani.classList.add('hide');
        mortis.classList.add('hide');
        mrp.classList.add('hide');
        sprout.classList.add('hide');
        gene.classList.add('hide');
        max.classList.add('hide');
        spike.classList.add('hide');
        crow.classList.add('hide');
        leon.classList.add('hide');
        sandy.classList.add('hide');
        gale.classList.add('hide');
        surge.classList.add('hide');
        fall.classList.add('hide');
        back.classList.remove('hide');
        ff.classList.remove('hide');
        pipe.classList.remove('hide');
        cereal.play();
      }
    
    </script>

  </body>

</html>

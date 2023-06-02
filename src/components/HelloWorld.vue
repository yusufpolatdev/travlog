<script>
export default {
  methods: {
    shouldHideRight(index) {
      return index % 4 === 2;
    },
    shouldHideLeft(index) {
      return index % 4 === 3;
    }
  }
}
</script>

<template>
  <div class="main-header">
  <div class="background-left"></div>

<div class="header">
  <div class="navbar">
    <div class="logo">
      <div class="logo-img">
    <img src="src/assets/logo.png">
      </div>
      <div class="logo-title">
        <p> Travlog </p>

      </div>
    </div>

    <div class="nav">
      <ul class="nav-list">
        <li class="nav-item">Home</li>
        <li class="nav-item">Discover</li>
        <li class="nav-item">Categories</li>
        <li class="nav-item">Top Users</li>
      </ul>

    </div>

    <div class="navbar-buttons">
      <button class="log-in-button"> Log In  </button>
      <button class="promote-button"> 🚀 Promote</button>
    </div>
  </div>

  <div class="header-search">
    <div class="arrow-column">
      <div v-for="index in 20" :key="index" class="arrow">
        <div class="arrow-img" :class="{ 'hidden': shouldHideRight(index) || shouldHideLeft(index) }">
          <img src="src/assets/arrow.png">
        </div>
      </div>

    </div>
    <div class="column">
    <div class="search-text">
      <span> Search OnlyFans Accounts and Find the <span class="onlyfans-text"> Best OnlyFans </span> Girls  </span>
      <span class="onlyfans-text-detail"> Use our OnlyFans Finder and search in all the existing accounts  </span>
    </div>

    <div class="search">
      <div class="search-box">
        <img src="src/assets/Vector.png">
        <input type="text" placeholder="Search Onlyfans by Name, instagram..">
        <button class="search-button">Search</button>
      </div>
      <div class="tags">
      <button>  Mia khalifa</button>
        <button>  Bella Bumzy </button>
        <button>  Sam Slayres </button>
      </div>

    </div>
    <div class="icon-img">
      <img class="woman-image-1" src="src/assets/woman-image.png">
      <img class="woman-image-2" src="src/assets/woman-image-2.png">
      <img class="woman-image-3" src="src/assets/woman-image-3.png">
    </div>
    </div>

  </div>


</div>

  <div class="background-right">

  </div>
  </div>

  <div class="content">
    <div class="most-trending">
      <div class="most-trending-title">

        <span class="most-trending-main-title"> MOST TRENDING </span>
          <span class="most-trending-subtitle"> Hottest OnlyFans Accounts</span>

      </div>

      <div class="most-trending-models">

      <div class="most-trending-content">
        <div class="models-img"> <img src="src/assets/Rectangle%2019.png"></div>
        <div class="models-name">
          <div class="models-username">
            <div class="model-info">
              <div class="verified-model">
              <span>Devon Lane</span>
                <div class="verified-icon">
                <img src="src/assets/purple-background.png" class="background-img">
                <img src="src/assets/Vector%20559%20(Stroke).png" class="foreground-img">
                </div>
              </div>
              <div class="model-username">
              <span> @devonlane </span>
              </div>
          </div>

          </div>
          <div class="models-rate">
            <div>
            <img src="src/assets/star.png">
            </div>
            <span> 4.5 </span>
          </div>
        </div>
        <div class="models-tags">
          <div class="model-tag">  <div> <img src="src/assets/star.png"> </div> <span> Boost User </span> </div>
          <div class="model-tag-2"> <span> Free </span> </div>
        </div>

      </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2021.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Guy Hawkins</span>

                </div>
                <div class="model-username">
                  <span> @guyhawing12 </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">
            <div class="model-tag-2"> <span> 12$ </span> </div>
          </div>

        </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2022.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Cameron Williamson</span>

                </div>
                <div class="model-username">
                  <span> @cameetronn </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">
            <div class="model-tag-2"> <span> 5$ </span> </div>
          </div>

        </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2018.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Floyd Miles</span>

                </div>
                <div class="model-username">
                  <span> @floykkmilsss </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">

            <div class="model-tag-2"> <span> 9.99$ </span> </div>
          </div>

        </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2029.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Courtney Henry</span>
                  <div class="verified-icon">
                    <img src="src/assets/purple-background.png" class="background-img">
                    <img src="src/assets/Vector%20559%20(Stroke).png" class="foreground-img">
                  </div>
                </div>
                <div class="model-username">
                  <span> @hentrycourtney </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">

            <div class="model-tag-2"> <span> Free </span> </div>
          </div>

        </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2030.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Kristin Watson </span>

                </div>
                <div class="model-username">
                  <span> @kristineee </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">

            <div class="model-tag-2"> <span> 12$ </span> </div>
          </div>

        </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2031.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Cody Fisher</span>

                </div>
                <div class="model-username">
                  <span> @coddyfishher </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">
            <div class="model-tag-2"> <span> 5$ </span> </div>
            <div class="model-tag">  <div> <img src="src/assets/star.png"> </div> <span> Boost User </span> </div>

          </div>

        </div>
        <div class="most-trending-content">
          <div class="models-img"> <img src="src/assets/Rectangle%2028.png"></div>
          <div class="models-name">
            <div class="models-username">
              <div class="model-info">
                <div class="verified-model">
                  <span>Theresa Webb</span>

                </div>
                <div class="model-username">
                  <span> @thresawebb </span>
                </div>
              </div>

            </div>
            <div class="models-rate">
              <div>
                <img src="src/assets/star.png">
              </div>
              <span> 4.5 </span>
            </div>
          </div>
          <div class="models-tags">

            <div class="model-tag-2"> <span> 9.99$ </span> </div>
          </div>

        </div>
    </div>



    </div>

    <div class="categories">
      <div class="categories-title">
        <div class="categories-main-title">
          <span> Categories </span>

        </div>

        <div class="categories-description">
          <span> Are you looking for Asian Onlyfans or Famous people with account? We have all the accounts classified by the most common categories and hashtags </span>
        </div>

      </div>

      <div class="categories-content">
      <button> <span> Amateur </span></button>
        <button> <span> Asian </span></button>
        <button> <span> Cosplay </span></button>
        <button> <span> Ebony </span></button>
        <button> <span> Pregnant </span></button>
        <button> <span> Explicit </span></button>
        <button> <span> Milf </span></button>
        <button> <span> Couples </span></button>
        <button> <span> Girls </span></button>
        <button> <span> Petite </span></button>
        <button> <span> Piercing </span></button>
        <button> <span> Pornstar </span></button>
        <button> <span> Fetish </span></button>
        <button> <span> Findom </span></button>
        <button> <span> Chubby </span></button>
        <button> <span> Goth </span></button>
        <button> <span> Trans </span></button>
        <button> <span> Teens </span></button>
        <button> <span> Latins  </span></button>


      </div>


    </div>

    <div class="location">
      <div class="location-title">
        <div class="location-main-title"> <span> Location </span> </div>
        <div class="location-description"> <span> Do you want to find OnlyFans accounts by location, city, Country or near you? We have the profiles classified by location, so you can easily follow accounts near you and meet the best Content Creators in person! </span></div>
      </div>

      <div class="location-contents">
        <div class="location-content">
          <div class="location-img">
            <img src="src/assets/england.png">
          </div>
          <div class="location-name"> <span> United Kingdom </span> </div>

        </div>
        <div class="location-content">
          <div class="location-img">
            <img src="src/assets/france.png">
          </div>
          <div class="location-name"> <span> France </span> </div>

        </div>
        <div class="location-content">
          <div class="location-img">
            <img src="src/assets/spain.png">
          </div>
          <div class="location-name"> <span> Spanish </span> </div>

        </div>
        <div class="location-content">
          <div class="location-img">
            <img src="src/assets/romania.png">
          </div>
          <div class="location-name"> <span> Romania </span> </div>

        </div>
        <div class="location-content">
          <div class="location-img">
            <img src="src/assets/france.png">
          </div>
          <div class="location-name"> <span> Turkey </span> </div>

        </div>
        <div class="location-content">
          <div class="location-img">
            <img src="src/assets/germany.png">
          </div>
          <div class="location-name"> <span> Germany </span> </div>

        </div>
        <div class="location-content">

          <div class="location-name see-all"> <span> SEE ALL </span> </div>

        </div>
      </div>

    </div>



  </div>


  <div class="footer">
    <div class="policy">
      <div class="logo">
        <div class="logo-img">
          <img src="src/assets/logo.png">
        </div>
        <div class="logo-title">
          <span> Oxfans </span>

        </div>
      </div>
      <div class="policy-desc">
        <p> <span> Conditions </span>  and <span> Privacy Policy. </span> This website is protected by reCAPTCHA and Google <span> Privacy Policy</span>  and <span> Terms of Service </span>  apply. </p>

      </div>

      <div class="socials">
        <div class="facebook"> <img src="src/assets/facebook.png"> </div>
        <div class="twitter"> <img src="src/assets/twitter.png"> </div>
        <div class="instagram"> <img src="src/assets/instagram.png"> </div>

      </div>

    </div>
    <div class="company">
      <div class="footer-title"> <span> Company </span></div>
      <div class="footer-content">
      <span> About </span>
        <span>Career</span>
        <span> Mobile </span>
      </div>

    </div>
    <div class="contact">
      <div class="footer-title "><span> Contact </span> </div>
      <div class="footer-content">
        <span> Why Oxfans </span>
        <span>Partner with us</span>
        <span> FAQ’s </span>
        <span> Blog </span>
      </div>

    </div>
    <div class="meet-us">
      <div class="footer-title"><span> Meet Us </span> </div>
      <div class="footer-content">
        <span> +00 92 1234 56789 </span>
        <span>info@oxfans.com</span>
        <span> 205. R Street, New York  </span>
        <p>BD23200 </p>

      </div>
    </div>


  </div>
</template>

<style>


body {
  margin:0;
  padding: 0;

}

.main-header {
  display: flex;
  position: relative;
}
.background-right{
position: absolute;
  width: 35%;
right: 0;
  height: 500px;
  background-color: #FACD49;
  opacity: 0.6;
  filter: blur(250px);
}
.background-left {
position: absolute;
  width: 35%;
  height: 400px;
  background-color: #FF5722;
  opacity: 0.5;
  filter: blur(250px);
}

.header {
  height: 450px;
width: 100%;
  z-index: 1;

}

.navbar {
  height: auto;

  display: flex;
width: 65%;
  margin: auto;
padding: 10px;

  align-items: center;

}

.logo {
  display: flex;
  align-items: center;

}

.logo-img {
margin-right: 20px;
}

.logo-title {
font-family: Poppins;
  font-weight: 900;
  font-size: 24px;


}
.nav {

  margin-left: 140px;
}

.nav-list {
  list-style-type: none;
  margin: 0;
  padding: 0px;
  display: flex;
}

.nav-item {
  margin-right: 64px;
  cursor: pointer;
  color: rgba(25, 24, 37, 0.5);
  font-family: "Circular Std Bold";
  white-space: nowrap;
  font-size: 14px;

}

.nav-item:first-child {
  color:#222831
}

.nav-item:last-child {
  margin-right: 0;
}

.navbar-buttons {
margin-left: 140px;
  display: flex;
}

.log-in-button {
  border-radius: 100px;
  background-color: #FFFFFF;
  padding: 16px 32px;
  border: none;
  cursor: pointer;
  font-family: "Circular Std Bold";
  font-size: 14px;
  color: #222831;
  margin-right: 10px;
  white-space: nowrap;


}

.promote-button {
  border-radius: 100px;
  background-color: #5D50C6;
  padding: 16px 32px;
  border: none;
  cursor: pointer;
  font-size: 14px;
  color: white;
  font-family: "Circular Std Bold";
  white-space: nowrap;


}

.header-search {
  display: flex;
  margin: auto;
 width: 1200px;
  padding-top: 50px;
}
.search-text {
  font-family: "Circular Std Bold";
width: 900px;
  font-size: 47px;
  display: flex;
  flex-direction: column;
  margin-bottom: 30px;

}

.onlyfans-text {
  color: rgb(248, 94, 159, 1);

}

.onlyfans-text-detail {
  font-family: Inter;
  font-weight: 400;
  font-style: normal;
  font-size: 18px;
  color: rgba(25, 24, 37, 0.5);
  margin-top: 12px;
  line-height: 160%;
}

.search-box {
position: relative;
  width: 60%;
  height: 65px;



}

.search-box input {

  width: 100%;
  height: 100%;
  border: none;
  outline: none;
  font-size: 17px;
  font-family: Inter;
  font-weight: 500;
  font-style: normal;
  border-radius: 10px;
  box-shadow: 0px 1px 16px rgba(0, 0, 0, 0.14);
  text-indent: 50px;

}

.search-box input::placeholder {
  color: rgba(25, 24, 37, 0.5);

}

.search-box img {
  position: absolute;
  top:24px;
  left:20px;
 width: 18px;
  height: 18px;
}
.search-button {
  position: absolute;
  background-color: #5D50C6;
  color: #EEEEEE;
  border: none;
  border-radius: 8px;
width: 104px;
  height: 42px;
  line-height: 17px;
  cursor: pointer;
  left: 430px;
  bottom: 10px;
  font-family: "Circular Std Bold";
  font-size:14px;
}

.tags {
margin-top: 22px;
}

.tags button {
  background: #FFFFFF;
  border: 0.5px solid #B0B0B0;
  border-radius: 100px;
  cursor: pointer;
  font-family: "Circular Std Medium";
  font-size:15px;
  width: 119px;
  height: 34px;
  margin-right: 11px;
}

.icon-img {
  position: relative;
  width: 113%;
}

.woman-image-1 {
  position: absolute;
  right: 150px;
  bottom: 60px;
}

.woman-image-2{
  position: absolute;
  right: 65px;

  bottom: 30px;
}

.woman-image-3 {
  position: absolute;
  right: 50px;
  bottom: 150px;
}

.arrow {
margin-right: 46px;

}


.arrow-column {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  width: 10%;
height: 149px;

}
.hidden {
  display: none;
}

.column {
  margin-left: 25px;
}

.content {

  margin-top: 84px;

}




.most-trending-title {
  display: flex;
  flex-direction: column;
  width: 65%;
  padding: 10px;
  margin: auto;



}

.most-trending-main-title {
font-family: "Circular Std Medium";
  font-weight: 700;
  letter-spacing: 0.2em;
  color: #F85E9F;
  font-size:16px;
  margin-bottom: 16px;
  line-height: 0%;
}

.most-trending-subtitle {
  font-family: "Circular Std Medium";
  font-weight: 700;
  color: #191825;
  font-size:30px;
  line-height: 120%;
  font-style: normal;
}

.most-trending-content {
  display: flex;
  flex-direction: column;
  margin-right: 22px;
  margin-bottom: 34px;



}

.verified-icon {
  display: flex;
  align-items: center;

  margin-left: 5px;
}

.verified-model {
  display: flex;
}

.foreground-img {
  position: relative;
  right: 11px;
}

.models-name {
  display: flex;
  justify-content: space-between;
}

.models-tags{
  display: flex;
  margin-top: 9px;
}

.model-tag {
  background: #FACD49;
  border-radius: 10px;
  font-family: 'Circular Std Medium';
  font-style: normal;
  font-size: 14px;
  line-height: 160%;
width: 105px;
  height: 25px;
display: flex;
  justify-content: center;
  color: #000000;
  align-items: center;
  margin-right: 9px;

}

.model-tag-2 {
  margin-right: 9px;
}

.model-tag div  {
  display: flex;
  align-items: center;
  margin-bottom: 2px;
  margin-right: 3px;

}
.model-tag div img {
  width: 15px;
  height: auto;
}

.verified-model span {
  font-family: 'Circular Std Bold';
  font-style: normal;
  font-size: 15px;
  line-height: 160%;



  color: #000000;
}

.model-username {
  font-family: 'Circular Std Book';
  font-style: normal;
  font-weight: 450;
  font-size: 15px;
  line-height: 160%;



  color: #2F2F2F;
}

.models-rate span {
  font-family: 'Circular Std';
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 160%;


  color: #000000;
}

.models-rate div img {

    width: 17px;
    height: auto;

}
.models-rate {
  display: flex;

}

.models-rate div {
margin-top: 4px;
  margin-right: 4px;
}

.model-tag-2 {

  background: #5D50C6;
  border-radius: 10px;
  width: 47px;
  height: 25px;
  display: flex;
  justify-content: center;
  align-items: center;

  font-family: 'Circular Std Medium';
  font-style: normal;
  font-size: 14px;
  line-height: 160%;


  color: #FFFFFF;
}

.most-trending-models {
  display: flex;
  flex-wrap: wrap;
  width: 68%;
  margin: auto;
padding-left: 48px;
padding-top: 24px;


}

.categories-title {
  display: flex;
  flex-direction: column;
  width: 65%;
  padding: 10px;
  margin: auto;
}

.categories-main-title {
  font-family: 'Circular Std Bold';
  font-style: normal;
  font-size: 30px;
  line-height: 120%;
  margin-bottom: 8px;

  color: #191825;

}

.categories-description {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 160%;
  color: rgba(25, 24, 37, 0.5);
}

.categories-content button {

    background: #FFFFFF;
    border: 1px solid #000000;
    box-shadow: 0px 139px 83px rgba(0, 0, 0, 0.01), 0px 62px 62px rgba(0, 0, 0, 0.02), 0px 15px 34px rgba(0, 0, 0, 0.03), 0px 0px 0px rgba(0, 0, 0, 0.03);
    border-radius: 100px;
    padding: 16px 32px;
    text-decoration: none;
    display: inline-block;
  font-family: 'Circular Std Bold';
  font-style: normal;
  font-size: 23px;
  line-height: 120%;
  gap: 16px;
  margin-right: 30px;
  margin-bottom: 30px;


  color: #191825;


}

.categories-content {
  display: flex;
  flex-wrap: wrap;
  width: 65%;
  margin: auto;
  padding-top: 24px;

}

.categories-content button:hover {
  background: #000000;
  color: #FFFFFF;
}

.location-title {
  display: flex;
  flex-direction: column;
  width: 65%;
  padding: 10px;
  margin: auto;
}

.location-main-title {
  font-family: 'Circular Std Bold';
  font-style: normal;
  font-size: 30px;
  line-height: 120%;
  margin-bottom: 8px;

  color: #191825;
}

.location-description {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 160%;
  color: rgba(25, 24, 37, 0.5);
}

.location-contents {
  display: flex;
  flex-wrap: wrap;
  width: 75%;
  margin: auto;
  padding-left: 168px;

}

.location-content {
  margin-right: 40px;
  text-align: center;
  margin-top: 20px;
  display: flex;
justify-content: center;
  flex-direction: column;

}

.location-name {

  font-family: 'Circular Std';
  font-style: normal;
  font-weight: 700;
  font-size: 23px;
  line-height: 120%;
  margin-top: 18px;
  color: #191825;

}

.see-all {
  width: 115px;
  height: 115px;
  border-radius: 50%;
  background: #5D50C6;
  font-family: 'Circular Std Book';
  font-style: normal;
  font-weight: 450;
  font-size: 18px;
  line-height: 160%;
  align-items: center;
  display: flex;
  justify-content: center;
margin-bottom: 65px;


  color: #FFFFFF

}

.footer {
  display: flex;
  width: 65%;
  padding: 168px 10px 10px 10px;
  margin: auto;
  justify-content: space-between;
  flex-wrap: wrap;



}

.footer-title {
  font-family: 'Circular Std Bold';
  font-style: normal;
  font-weight: 700;
  font-size: 23px;
  line-height: 120%;


  color: #191825;

}

.footer-content {
  display: flex;
  flex-direction: column;

}

.footer-content span {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 160%;
margin-top: 32px;
  color: rgba(25, 24, 37, 0.75);

}

.footer-content p {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 160%;
  color: rgba(25, 24, 37, 0.75);
}



.policy-desc {
  font-family: 'Circular Std Book';
  font-style: normal;
  font-weight: 450;
  font-size: 23px;
  line-height: 160%;




  color: rgba(25, 24, 37, 0.5);
}

.contact, .company {
  margin-right: 20px;
}

.policy-desc span {
  text-decoration-line: underline;
}

.policy {
  width: 280px;
  margin-right: 60px;

}

.socials {
  display: flex;
  margin-top: 64px;
}

.facebook {
  margin-right: 32px;
}

.twitter {
  background: #5D50C6;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 32px;
}
.instagram {

    background: #5D50C6;
    width: 32px;
    height: 32px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;

}

@media screen and (max-width: 768px) {

  .promote-button,
  .arrow-column, .nav, .logo-title {
    display: none;
  }

  .navbar {
    width: 100%;
    display: flex;
    justify-content: space-between;
    padding: 0;
  }

  .log-in-button {
    margin: 0;
  }

  .header{
    width: 100%;
  }

  .column {
    display: flex;
    flex-direction: column;
  }

  .nav {
    display: none;
  }



  .nav-list {
    display: flex;
    flex-direction: column;
  }

  .nav-item {
    margin-bottom: 10px;
  }

  .main-header {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .background-left,
  .background-right {
width: 50%;
  }

  .header-search {
width: 100%;
  }

  .arrow {
    display: flex;
    justify-content: center;
  }

  .arrow-img {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .search,
  .tags {
    flex-direction: column;
  }

  .search-box {
    display: flex;
    flex-direction: column;
    width: 100%;
  }

  .search-button {
    margin-top: 10px;
  }

  .icon-img {
    display: none;
  }

  .content {
    padding: 10px;
  }



  .categories-content,
  .location-contents {
    display: grid;
    grid-template-columns: repeat(2);
    gap: 10px;
  }
  .search-text {
    width: 100%;
    font-size: 26px;
  }

  .most-trending-models, .categories-content, .location, .footer, .categories-title, .location-contents, .location-title {
    padding-left: 0;
    width: 100%;
  }

  .location-content {
    align-items: center;
  }

  .most-trending-title {
    width: 100%;
  }

  body {
    padding: 20px;
  }
  .onlyfans-text-detail {
    font-size: 15px;
  }

  .column {
    margin-left: 0
  }
  .search-button {

    left: 65%;

  }

  .tags button {
    margin-bottom: 5px;
  }
  .search-box input::placeholder {
    font-size: 14px;
  }
.footer div {
  margin-bottom: 10px;
}

}






</style>

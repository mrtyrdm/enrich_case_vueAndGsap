
<template>
    
    <nav class="fixed right-5 top-5 z-50">
        <div  v-on:click="goto('home')" class="cursor-pointer	 w-16 h-16 m-2 bg-green-900 rounded-md bg-amber-500 text-white flex items-center justify-center text-2xl font-extrabold"><svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6" />
</svg></div>
        <div  v-on:click="goto('one')" class="cursor-pointer	 w-16 h-16 m-2 bg-green-900 rounded-md bg-amber-500 text-white flex items-center justify-center text-2xl font-extrabold">1</div>
        <div   v-on:click="goto('two')"  class="cursor-pointer	 w-16 h-16 m-2  bg-green-900 rounded-md bg-amber-500 text-white flex items-center justify-center text-2xl font-extrabold">2</div>
        <div    v-on:click="goto('three')" class="cursor-pointer	w-16 h-16 m-2  bg-green-900 rounded-md bg-amber-500 text-white flex items-center justify-center text-2xl font-extrabold">3</div>

    </nav>

    <section id="home" ref="home" class="relative flex items-center justify-center w-full min-h-screen	bg-green-300">
        <div class=" text-center m-auto 	w-full h-full">
        <div class="max-w-6xl mx-auto sm:px-6 lg:px-8  top-0 left-0">
            <div id="homeContent" class="p-20">
              <h2 class="font-bold mb-5 text-3xl text-white">{{text}}</h2>
              <p class="text-2xl">Animasyon için yandaki buttonlara basarak ilerleyebilirsinz.</p>
              <div class="flex justify-center py-6">
                <a  target="_blank" href="https://github.com/mrtyrdm">
                <div class="box p-5 bg-gray-800 rounded"><span class="text-white font-black">GitHub</span></div>
                </a>
                <div class="box"></div>
              </div>
            </div>
          </div>
        </div>
    </section>

    <section id="one" ref="one"  class="relative z-10  w-full min-h-screen bg-red-300">
      <div class="m-auto w-full h-full">

      <div class="max-w-6xl mx-auto sm:px-6 lg:px-8  top-0 left-0">
          <div class="flex p-5 justify-center items-center">
            <div class="absolute text-9xl">
              <div class="text-white font-black flex textAni"><div class="z-0" >Made</div> <div class="z-20"> With Love</div></div>
            </div>
          
          <img class="headphone z-10" src="./assets/images/headphone.png" alt="">

          </div>
      </div>

      </div>
    </section>

    <section id="two" ref="two"  class="relative  w-full min-h-screen bg-white">

        
      <div class="m-auto w-full h-full z-20 relative">
        <div id="Group_1273s" class="max-w-6xl mx-auto sm:px-6 lg:px-8  top-0 left-0 ">
        <div class="flex w-full">
          <div class="w-6/12 ">
            <svg class="z-30" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="562.295" height="841.448" viewBox="0 0 562.295 841.448">
        <defs>
          <filter id="Shadow" x="0" y="0" width="562.295" height="841.448" filterUnits="userSpaceOnUse">
            <feOffset dx="65" dy="-16" input="SourceAlpha"/>
            <feGaussianBlur stdDeviation="48" result="blur"/>
            <feFlood flood-opacity="0.18"/>
            <feComposite operator="in" in2="blur"/>
            <feComposite in="SourceGraphic"/>
          </filter>
          <linearGradient id="linear-gradient" x1="0.5" x2="0.5" y2="1" gradientUnits="objectBoundingBox">
            <stop offset="0" stop-opacity="0.161"/>
            <stop offset="1" stop-color="#fff" stop-opacity="0"/>
          </linearGradient>
        </defs>
        <g id="Group_1272" data-name="Group 1272" transform="matrix(0.966, 0.259, -0.259, 0.966, 98.24, 92.926)">
          <path id="Rectangle_2145" data-name="Rectangle 2145" d="M0,0H0A4.559,4.559,0,0,1,4.559,4.559V46.473A4.559,4.559,0,0,1,0,51.032H0a0,0,0,0,1,0,0V0A0,0,0,0,1,0,0Z" transform="matrix(-0.966, 0.259, -0.259, -0.966, 61.643, 300.551)" fill="#fff"/>
          <path id="Rectangle_2146" data-name="Rectangle 2146" d="M0,0H0A4.559,4.559,0,0,1,4.559,4.559V46.473A4.559,4.559,0,0,1,0,51.032H0a0,0,0,0,1,0,0V0A0,0,0,0,1,0,0Z" transform="matrix(-0.966, 0.259, -0.259, -0.966, 45.387, 239.883)" fill="#fff"/>
          <path id="Rectangle_2147" data-name="Rectangle 2147" d="M0,0H0A4.559,4.559,0,0,1,4.559,4.559V22.92A4.559,4.559,0,0,1,0,27.479H0a0,0,0,0,1,0,0V0A0,0,0,0,1,0,0Z" transform="matrix(-0.966, 0.259, -0.259, -0.966, 26.422, 169.104)" fill="#fff"/>
          <g id="Device" transform="matrix(0.966, -0.259, 0.259, 0.966, 0, 70.475)">
            <path id="Change_Color" data-name="Change Color" d="M0,275.822Q0,157.968.021,40.114C.026,27.535,4.962,17.036,14.154,8.551A30.928,30.928,0,0,1,30.728.422,33.551,33.551,0,0,1,35.734.061Q111.459.034,187.183.047c15.9,0,31.794.126,47.689-.045,10.342-.111,18.764,3.8,25.646,11.271a42.372,42.372,0,0,1,11.26,25.271c.121,1.26.079,2.537.079,3.806q0,145.279,0,290.558,0,90.352.055,180.7c.033,14.9-9.944,30.478-23.622,36.714a32.263,32.263,0,0,1-13.582,2.911q-81.362-.026-162.725-.012c-11.326,0-22.653-.109-33.977.035a33.871,33.871,0,0,1-23.276-8.671A41.232,41.232,0,0,1,.538,518.042a39.489,39.489,0,0,1-.514-6.818Q-.022,454.773,0,398.322q0-61.25,0-122.5" transform="translate(0.152 0.153)" fill="#fefefe"/>
            <g transform="matrix(1, 0, 0, 1, -80, -161)" filter="url(#Shadow)">
              <path id="Shadow-2" data-name="Shadow" d="M38.119,0H234.177A38.119,38.119,0,0,1,272.3,38.119v475.21a38.119,38.119,0,0,1-38.119,38.119H38.119A38.119,38.119,0,0,1,0,513.329V38.119A38.119,38.119,0,0,1,38.119,0Z" transform="translate(80 161)" fill="#fff" stroke="#f0f0f0" stroke-width="2"/>
            </g>
          </g>
          <path id="Border" d="M.024,260.713q0-107.871,0-215.74c0-7.058-.1-14.121.076-21.176A24.731,24.731,0,0,1,19.457.675,28.172,28.172,0,0,1,25.349.045q11.808,0,23.612-.006a3.717,3.717,0,0,1,3.034,1.112,3.536,3.536,0,0,1,.837,2.386,25.437,25.437,0,0,0,.427,5,13.5,13.5,0,0,0,13.1,10.71c9.7.078,19.4.027,29.1.029q38.39,0,76.779,0a19.022,19.022,0,0,0,3.942-.265,13.709,13.709,0,0,0,10.954-12.78c.05-.963.04-1.931.11-2.892A3.232,3.232,0,0,1,190.7.059c8.429-.018,16.862-.148,25.288.047a24.646,24.646,0,0,1,23.352,18.119,21.7,21.7,0,0,1,.873,6.157q-.015,25.447,0,50.889,0,209.643.015,419.3a27.221,27.221,0,0,1-1.509,10.316q-5.364,13.394-19.557,15.969a27.573,27.573,0,0,1-5.01.3H30.886c-2.234,0-4.471.031-6.7-.046A24.829,24.829,0,0,1,.356,500.359a30.169,30.169,0,0,1-.326-5.166Q.023,416.339.027,337.5V260.713Z" transform="matrix(0.966, -0.259, 0.259, 0.966, 19.419, 80.897)" fill="#5766e9"/>
          <path id="Rectangle_2148" data-name="Rectangle 2148" d="M0,0H0A4.559,4.559,0,0,1,4.559,4.559V67.564A4.559,4.559,0,0,1,0,72.123H0a0,0,0,0,1,0,0V0A0,0,0,0,1,0,0Z" transform="matrix(0.966, -0.259, 0.259, 0.966, 295.233, 120.106)" fill="#fff"/>
          <g id="Group_1128" data-name="Group 1128" transform="matrix(0.966, -0.259, 0.259, 0.966, 101.484, 59.714)">
            <rect id="Rectangle_2101" data-name="Rectangle 2101" width="35.348" height="5.163" rx="2.582" transform="translate(16.644 2.581)" opacity="0.054"/>
            <g id="Group_1126" data-name="Group 1126" transform="translate(0 0)">
              <ellipse id="Ellipse_1096" data-name="Ellipse 1096" cx="5.163" cy="5.163" rx="5.163" ry="5.163" transform="translate(60.177 0)" fill="url(#linear-gradient)"/>
              <ellipse id="Ellipse_1098" data-name="Ellipse 1098" cx="3.421" cy="3.421" rx="3.421" ry="3.421" transform="translate(0 1.741)" fill="#f0f0f0"/>
              <ellipse id="Ellipse_1097" data-name="Ellipse 1097" cx="2.213" cy="2.213" rx="2.213" ry="2.213" transform="translate(63.127 2.95)" fill="#035a81" opacity="0.15"/>
            </g>
          </g>
        </g>
            </svg>
          </div>

            <div class="flex w-6/12  items-center justify-center  flex-col ml-36">
          
                  <h3 class="text-5xl w-full mb-16 font-bold">Lorem Ipsum</h3>
                <p>Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita.</p>
                </div>
        
          <div>

            
            
          </div>
        </div>

        </div>
      </div>

      <div id="Group_1273s z-0">
        <svg id="desing2" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="1240.622" height="1604.984" viewBox="0 0 1240.622 1604.984">
            
            <g id="Group_1273"  transform="translate(235.353 -2604.639)">
              <path  id="Subtraction_51"  d="M802.506,1604.984h0v0h-.054a814.776,814.776,0,0,1-82-4.137,804.89,804.89,0,0,1-79.68-12.165c-25.849-5.289-51.726-11.941-76.909-19.773-24.912-7.752-49.72-16.83-73.732-26.984-23.786-10.062-47.385-21.434-70.146-33.8-22.523-12.228-44.787-25.749-66.174-40.19a807.16,807.16,0,0,1-216.759-216.762c-14.369-21.266-27.893-43.527-40.2-66.165-12.341-22.709-23.7-46.311-33.787-70.153-10.179-24.056-19.257-48.86-26.988-73.726-7.827-25.172-14.479-51.046-19.774-76.906A806.022,806.022,0,0,1,4.143,884.542a814.544,814.544,0,0,1,0-164.1,804.278,804.278,0,0,1,12.163-79.681C21.6,614.9,28.251,589.029,36.08,563.855,43.807,539,52.885,514.2,63.068,490.128c10.07-23.813,21.437-47.415,33.787-70.153,12.284-22.607,25.809-44.868,40.2-66.163A807.161,807.161,0,0,1,353.812,137.049c21.372-14.429,43.639-27.954,66.174-40.2,22.68-12.324,46.283-23.692,70.146-33.791,24.074-10.18,48.882-19.259,73.732-26.982,25.183-7.834,51.06-14.486,76.909-19.775a804.111,804.111,0,0,1,79.68-12.163A814.248,814.248,0,0,1,802.5,0l0,229.852-.031,0a576.758,576.758,0,0,0-115.381,11.631A569.542,569.542,0,0,0,482.332,327.65a574.326,574.326,0,0,0-207.469,251.94,570.077,570.077,0,0,0-33.374,107.491,578.572,578.572,0,0,0,0,230.818,569.633,569.633,0,0,0,86.171,204.76,574.309,574.309,0,0,0,251.946,207.47A570.014,570.014,0,0,0,687.095,1363.5,577.374,577.374,0,0,0,802.5,1375.131Z" transform="translate(-235.353 2604.639)" fill="#5766e9"/>
              <path  id="Path_15"  d="M19930.285-12547.484a577.72,577.72,0,0,1-115.941-11.7,571.391,571.391,0,0,1-108-33.506,575.107,575.107,0,0,1-97.68-53.043,576.176,576.176,0,0,1-85.148-70.244,579.915,579.915,0,0,1-70.262-85.121,573.613,573.613,0,0,1-53.008-97.721,571.295,571.295,0,0,1-33.551-107.994,579.517,579.517,0,0,1-11.7-115.92,579.811,579.811,0,0,1,11.7-115.945,571.076,571.076,0,0,1,33.551-107.967,573.7,573.7,0,0,1,53.008-97.723,581.785,581.785,0,0,1,70.262-85.137,576.557,576.557,0,0,1,85.148-70.246,574.678,574.678,0,0,1,97.68-53.039,572.612,572.612,0,0,1,108-33.518,579.711,579.711,0,0,1,115.941-11.687v164.773h-.023a407.952,407.952,0,0,0-159.754,32.254,410.572,410.572,0,0,0-69.734,37.852,412.113,412.113,0,0,0-60.738,50.139,414.079,414.079,0,0,0-50.156,60.734,410.75,410.75,0,0,0-37.84,69.73,407.909,407.909,0,0,0-32.242,159.779,407.989,407.989,0,0,0,32.242,159.775,410.7,410.7,0,0,0,37.84,69.725,412.6,412.6,0,0,0,50.156,60.76,412.951,412.951,0,0,0,60.738,50.125,411.6,411.6,0,0,0,69.734,37.838,407.786,407.786,0,0,0,159.777,32.258v164.766Z" transform="translate(-19363.133 16529.869)" fill="#f7af75"/>
              <ellipse id="Ellipse_1110" data-name="Ellipse 1110" cx="424.553" cy="424.433" rx="424.553" ry="424.433" transform="translate(156.162 2982.697)" fill="#fbf7f6"/>
              <ellipse id="Ellipse_1111" data-name="Ellipse 1111" cx="331.329" cy="331.329" rx="331.329" ry="331.329" transform="translate(249.387 3069.911)" fill="#fe6150"/>
              
            </g>
          </svg>  

      </div>
    </section>

    <section id="three" ref="three"  class="relative  w-full min-h-screen bg-blue-500">
      <div class="m-auto w-full h-full relative">

      <div class="max-w-6xl mx-auto sm:px-6 lg:px-8  top-0 left-0 relative">
          <div id="navbar" class="flex items-start w-full py-20">
            <div class="flex justify-items-start w-full">
                <svg xmlns="http://www.w3.org/2000/svg" width="35" height="35" viewBox="0 0 35 35">
                <g id="Group_6" data-name="Group 6" transform="translate(-180 -72)">
                  <circle id="Ellipse_14" data-name="Ellipse 14" cx="7.5" cy="7.5" r="7.5" transform="translate(195 72) rotate(90)" fill="#fff"/>
                  <circle id="Ellipse_15" data-name="Ellipse 15" cx="7.5" cy="7.5" r="7.5" transform="translate(195 92) rotate(90)" fill="#fff200"/>
                  <circle id="Ellipse_16" data-name="Ellipse 16" cx="7.5" cy="7.5" r="7.5" transform="translate(215 72) rotate(90)" fill="#ec088c"/>
                  <circle id="Ellipse_17" data-name="Ellipse 17" cx="7.5" cy="7.5" r="7.5" transform="translate(215 92) rotate(90)"/>
                </g>
              </svg>

              <span class="leading-6 p-2 font-semibold uppercase  ">Ürünler</span>

            </div>
            <ul class="flex justify-items-end" >
              <li class="mr-6">
                <a class="text-black hover:text-gray-50 font-bold" href="#">TR</a>
              </li>
              <li class="mr-6">
                <a class="text-black hover:text-gray-50" href="#">AZ</a>
              </li>
              <li class="mr-6">
                <a class="text-black hover:text-gray-50" href="#">RU</a>
              </li>
              <li class="mr-6">
                <a class="text-gray-400 cursor-not-allowed" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="28.344" height="28.344" viewBox="0 0 28.344 28.344">
                  <g id="Icon_feather-search" data-name="Icon feather-search" transform="translate(-3 -3)">
                    <path id="Path_439" data-name="Path 439" d="M26.475,15.488A10.988,10.988,0,1,1,15.488,4.5,10.988,10.988,0,0,1,26.475,15.488Z" transform="translate(0)" fill="none" stroke="#000" stroke-linecap="round" stroke-linejoin="round" stroke-width="3"/>
                    <path id="Path_440" data-name="Path 440" d="M30.95,30.95l-5.975-5.975" transform="translate(-1.727 -1.727)" fill="none" stroke="#000" stroke-linecap="round" stroke-linejoin="round" stroke-width="3"/>
                  </g>
                </svg>
                </a>
              </li>
            </ul>

          </div>


            <div class="flex items-center w-full my-20">
                <div class="menu">
                  <svg xmlns="http://www.w3.org/2000/svg" width="24" height="28.116" viewBox="0 0 24 28.116">
                    <g id="Component_1_2" data-name="Component 1 – 2" transform="translate(1)">
                      <g id="Group_8" data-name="Group 8" transform="translate(-80.994 28.116) rotate(-90)">
                        <line id="Line_8" data-name="Line 8" y2="28.116" transform="translate(28.116 80.994) rotate(90)" fill="none" stroke="#000" stroke-width="2"/>
                        <line id="Line_9" data-name="Line 9" y2="28.116" transform="translate(28.116 91.994) rotate(90)" fill="none" stroke="#000" stroke-width="2"/>
                        <line id="Line_10" data-name="Line 10" y2="28.116" transform="translate(28.116 102.994) rotate(90)" fill="none" stroke="#000" stroke-width="2"/>
                      </g>
                    </g>
                </svg>
                </div>

              <div class="min-w-xs flex justify-center"> 
<div id="Group_3">
  <svg class="Path_1" viewBox="-614.926 -775.124 554.715 230.109">
    <path id="Path_1" d="M -614.3854370117188 -545.0142822265625 C -614.3854370117188 -545.0142822265625 -617.5975952148438 -652.7738647460938 -608.3641357421875 -710.3012084960938 C -599.1306762695312 -767.8285522460938 -577.45166015625 -775.123779296875 -577.45166015625 -775.123779296875 L -103.6962509155273 -775.123779296875 C -103.6962509155273 -775.123779296875 -80.42707061767578 -767.8285522460938 -69.57551574707031 -710.3012084960938 C -58.72396087646484 -652.7738647460938 -60.29004287719727 -545.0142822265625 -60.29004287719727 -545.0142822265625 L -614.3854370117188 -545.0142822265625 Z">
    </path>
  </svg>
  <svg class="Path_2_v" viewBox="-614.926 -775.124 554.715 230.109">
    <linearGradient id="Path_2_v" spreadMethod="pad" x1="0.5" x2="0.5" y1="0" y2="1">
      <stop offset="0" stop-color="#f7f7f7" stop-opacity="1"></stop>
      <stop offset="0.2414" stop-color="#fff" stop-opacity="1"></stop>
      <stop offset="0.5256" stop-color="#fff" stop-opacity="1"></stop>
      <stop offset="1" stop-color="#e5e5e5" stop-opacity="1"></stop>
    </linearGradient>
    <path id="Path_2_v" d="M -614.3854370117188 -545.0142822265625 C -614.3854370117188 -545.0142822265625 -617.5975952148438 -652.7738647460938 -608.3641357421875 -710.3012084960938 C -599.1306762695312 -767.8285522460938 -577.45166015625 -775.123779296875 -577.45166015625 -775.123779296875 L -103.6962509155273 -775.123779296875 C -103.6962509155273 -775.123779296875 -80.42707061767578 -767.8285522460938 -69.57551574707031 -710.3012084960938 C -58.72396087646484 -652.7738647460938 -60.29004287719727 -545.0142822265625 -60.29004287719727 -545.0142822265625 L -614.3854370117188 -545.0142822265625 Z">
    </path>
  </svg>
  
    
  
</div>  

                  <img class="relative w-8/12	"  src="./assets/images/Mask_Group_2.png" alt="">
              </div>

              <div class="scroll">
                <svg xmlns="http://www.w3.org/2000/svg" width="25.243" height="47.05" viewBox="0 0 25.243 47.05">
                  <g id="Icon_feather-arrow-down" data-name="Icon feather-arrow-down" transform="translate(-5.379 17.05)">
                    <path id="Path_441" data-name="Path 441" d="M18,7.5V51.55" transform="translate(0 -23.05)" fill="none" stroke="#000" stroke-linecap="round" stroke-linejoin="round" stroke-width="3"/>
                    <path id="Path_442" data-name="Path 442" d="M28.5,18,18,28.5,7.5,18" fill="none" stroke="#000" stroke-linecap="round" stroke-linejoin="round" stroke-width="3"/>
                  </g>
                </svg>
              </div>

            </div>


            <div class="flex items-end w-full">
                <div class="screol w-6/12">
                  <svg xmlns="http://www.w3.org/2000/svg" width="26.851" height="26.851" viewBox="0 0 26.851 26.851">
                  <g id="Group_5" data-name="Group 5" transform="translate(-174 -970.208)" opacity="0">
                    <path id="Path" d="M49.22,34.382H47.874c-1.056,0-1.26.5-1.26,1.236V37.24h2.518L48.8,39.78H46.613V46.3H43.987V39.78h-2.2V37.24h2.2V35.367a3.062,3.062,0,0,1,3.271-3.357,18.029,18.029,0,0,1,1.962.1Z" transform="translate(138.209 945.198)"/>
                    <path id="Fill-1" d="M44.6,37.951a9.345,9.345,0,0,1-9.331,9.871,9.217,9.217,0,0,1-5.033-1.491,6.551,6.551,0,0,0,4.861-1.374,3.291,3.291,0,0,1-3.068-2.3,3.256,3.256,0,0,0,1.482-.057A3.314,3.314,0,0,1,30.874,39.3a3.264,3.264,0,0,0,1.488.415,3.343,3.343,0,0,1-1.016-4.43,9.288,9.288,0,0,0,6.766,3.467,3.314,3.314,0,0,1,3.2-4.074,3.265,3.265,0,0,1,2.4,1.048,6.546,6.546,0,0,0,2.085-.8,3.327,3.327,0,0,1-1.443,1.836,6.5,6.5,0,0,0,1.885-.523A6.691,6.691,0,0,1,44.6,37.951" transform="translate(148.836 943.102)" fill-rule="evenodd"/>
                    <path id="Fill-1-2" data-name="Fill-1" d="M34.564,27.368c2.344,0,2.621.009,3.547.051a4.861,4.861,0,0,1,1.63.3,2.912,2.912,0,0,1,1.666,1.666,4.847,4.847,0,0,1,.3,1.63c.042.925.051,1.2.051,3.547s-.009,2.621-.051,3.547a4.839,4.839,0,0,1-.3,1.63,2.907,2.907,0,0,1-1.666,1.666,4.843,4.843,0,0,1-1.63.3c-.926.042-1.2.051-3.547.051s-2.621-.009-3.547-.051a4.843,4.843,0,0,1-1.63-.3,2.907,2.907,0,0,1-1.666-1.666,4.839,4.839,0,0,1-.3-1.63c-.042-.926-.051-1.2-.051-3.547s.009-2.621.051-3.547a4.847,4.847,0,0,1,.3-1.63,2.912,2.912,0,0,1,1.666-1.666,4.861,4.861,0,0,1,1.63-.3c.926-.042,1.2-.051,3.547-.051Zm0,2.689a4.508,4.508,0,1,1-4.508,4.507,4.508,4.508,0,0,1,4.508-4.507Zm0,7.433a2.926,2.926,0,1,1,2.926-2.926,2.926,2.926,0,0,1-2.926,2.926ZM40.3,29.878a1.053,1.053,0,1,1-1.053-1.053A1.053,1.053,0,0,1,40.3,29.878Zm-5.957-4.092c-2.185,0-2.495.011-3.4.053a6.435,6.435,0,0,0-2.131.408,4.492,4.492,0,0,0-2.567,2.567,6.446,6.446,0,0,0-.408,2.131c-.042.936-.053,1.235-.053,3.619s.01,2.683.053,3.619a6.446,6.446,0,0,0,.408,2.131,4.488,4.488,0,0,0,2.567,2.567,6.449,6.449,0,0,0,2.131.408c.937.043,1.235.053,3.619.053s2.683-.01,3.619-.053a6.449,6.449,0,0,0,2.131-.408,4.488,4.488,0,0,0,2.567-2.567,6.446,6.446,0,0,0,.408-2.131c.041-.907.052-1.216.053-3.4v-.435c0-2.186-.011-2.495-.053-3.4a6.446,6.446,0,0,0-.408-2.131,4.492,4.492,0,0,0-2.567-2.567,6.435,6.435,0,0,0-2.131-.408c-.907-.042-1.216-.053-3.4-.053Z" transform="translate(152.504 949.422)" fill-rule="evenodd"/>
                    <path id="Fill-1-3" data-name="Fill-1" d="M46.3,40.962H43.362v-5c0-1.371-.521-2.137-1.606-2.137-1.18,0-1.8.8-1.8,2.137v5H37.13V31.437h2.829V32.72a3.323,3.323,0,0,1,2.872-1.574c2.02,0,3.467,1.234,3.467,3.785ZM33.755,30.19h0A1.758,1.758,0,1,1,35.5,28.433a1.751,1.751,0,0,1-1.744,1.758ZM32.294,40.962h2.95V31.437h-2.95Z" transform="translate(147.915 948.818)" fill-rule="evenodd"/>
                  </g>
                  <g id="edit-unmask">
                    <path id="Path_494" data-name="Path 494" d="M17.055,6.028A4.028,4.028,0,1,1,13.028,2,4.028,4.028,0,0,1,17.055,6.028Z" transform="translate(0.398 -2)"/>
                    <path id="Path_495" data-name="Path 495" d="M15.37,12.685A2.685,2.685,0,1,1,12.685,10,2.685,2.685,0,0,1,15.37,12.685Z" transform="translate(0.74 0.74)"/>
                    <path id="Path_496" data-name="Path 496" d="M13.028,24.055A4.028,4.028,0,1,0,9,20.028,4.028,4.028,0,0,0,13.028,24.055Z" transform="translate(0.398 2.796)"/>
                    <path id="Path_497" data-name="Path 497" d="M24.055,13.028A4.028,4.028,0,1,1,20.028,9,4.028,4.028,0,0,1,24.055,13.028Z" transform="translate(2.796 0.398)"/>
                    <path id="Path_498" data-name="Path 498" d="M6.028,17.055A4.028,4.028,0,1,0,2,13.028,4.028,4.028,0,0,0,6.028,17.055Z" transform="translate(-2 0.398)"/>
                  </g>
                </svg>

                </div>

                
                <div class="tel w-6/12">
                  <div class="flex w-full justify-end">
                    <svg class="w-7" id="phone" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 26.851 26.851">
                    <path id="Path_971" data-name="Path 971" d="M25.425,15.425A13.426,13.426,0,0,0,12,2V4.685a10.74,10.74,0,0,1,10.74,10.74Z" transform="translate(1.425 -2)"/>
                    <path id="Path_972" data-name="Path 972" d="M2,12.055V5.343A1.343,1.343,0,0,1,3.343,4h6.713A1.343,1.343,0,0,1,11.4,5.343v5.37a1.343,1.343,0,0,1-1.343,1.343H7.37A10.74,10.74,0,0,0,18.111,22.8V20.111a1.343,1.343,0,0,1,1.343-1.343h5.37a1.343,1.343,0,0,1,1.343,1.343v6.713a1.343,1.343,0,0,1-1.343,1.343H18.111A16.111,16.111,0,0,1,2,12.055Z" transform="translate(-2 -1.315)"/>
                    <path id="Path_973" data-name="Path 973" d="M19.442,10.973a8.057,8.057,0,0,1,.613,3.083H17.639A5.638,5.638,0,0,0,12,8.417V6a8.055,8.055,0,0,1,7.442,4.973Z" transform="translate(1.425 -0.63)"/>
                  </svg></div>
                  

                </div>
            </div>


      </div>
      </div>
              

        <div class="absolute bottom-0 left-0 w-full">
          <svg class="w-full" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 1920 197.997">
<path id="Path_446" data-name="Path 446" d="M635-126.269s101.975-75.444,290.711-73.443,280.21,98.812,464.232,81.448,220.949-86.813,393.725-55.176,304.05,91.657,441.219,64.1,237.84-83.373,288.408-55.824,40.063,97.406,40.063,97.406H635Z" transform="translate(-635 199.751)" fill="#1aaced"/>
<path id="Path_445" data-name="Path 445" d="M635-126.269s101.975-75.444,290.711-73.443,280.21,98.812,464.232,81.448,220.949-86.813,393.725-55.176,304.05,91.657,441.219,64.1,237.84-83.373,288.408-55.824,40.063,97.406,40.063,97.406H635Z" transform="translate(-635 221.751)" fill="#ec088c"/>
<path id="Path_444" data-name="Path 444" d="M635-126.269s101.975-75.444,290.711-73.443,280.21,98.812,464.232,81.448,220.949-86.813,393.725-55.176,304.05,91.657,441.219,64.1,237.84-83.373,288.408-55.824,40.063,97.406,40.063,97.406H635Z" transform="translate(-635 243.751)" fill="#fff200"/>
<path id="Path_443" data-name="Path 443" d="M635-126.269s101.975-75.444,290.711-73.443,280.21,98.812,464.232,81.448,220.949-86.813,393.725-55.176,304.05,91.657,441.219,64.1,237.84-83.373,288.408-55.824,40.063,97.406,40.063,97.406H635Z" transform="translate(-634.262 265.751)"/>
</svg>

        </div>
      
      
    </section>

</template>


<script>


import { gsap } from "gsap";
import { ScrollTrigger } from 'gsap/ScrollTrigger';
import { ScrollToPlugin } from "gsap/ScrollToPlugin";


gsap.registerPlugin(ScrollTrigger,ScrollToPlugin);
  
const timeline = gsap.timeline({
      defaults:{duration: .5,ease:'Back.easeOuteaseOut' ,opacity:0}
});

export default {
  data() {
    return {
      count: 0,
      text : 'Enrich Techlonogy Animation Link'
    }
  },methods: {
  goto(refName) {
      var element = this.$refs[refName];
      var top = element.offsetTop;
       gsap.to(window, {duration: 1, scrollTo: top ,ease: "slow( 0.7 0.7, 0.7 0.7, false)"});
       if(refName=='home'){
         timeline.from('#homeContent', {opacity:0, y:-30,ease:"power2.out",stagger:20,duration: 1,})
         .from('.box',{y: -20, duration: 1.5, ease: " slow( 0.7 0.7, 0.7 0.7, false)",scale:1,}, "=.1");
        
       }
       if(refName=='one'){
      
        timeline.from(".headphone", { opacity: 0, y: 350, duration: 1.5,rotationX:30, ease: "circ.inOutinOut",scale:.1,clearProps: 'all'})
        .from('.textAni', {duration:1, opacity:0, stagger:.05, ease:"power2.in",clearProps: 'all'}, "=.1");
          
       } if(refName=='two'){

         gsap.from("#Ellipse_1110", { transformOrigin: "center 500px",  duration: 1, ease: "none"})
         gsap.from("#Path_15", { rotation: -40, duration: 1, ease: "none",} )
        
         timeline.from('#Subtraction_51', {delay: .1, scale: 1, transformOrigin: 'center' , rotation: 40,})        
         .from('#desing2',{scale:2, css:{left:'20%', width:'30%'}}, "=.1")
         .from('#Group_1273s', {y:80,}, "=.3")
         
        
       } if (refName=="three"){
          timeline.from('#navbar', {y: 20, duration: 1.5, ease: " slow( 0.7 0.7, 0.7 0.7, false)",scale:1,}).
          
          from('#Path_2_v',{opacity: 1, y: 300,duration: 1.5,}, "=.2");
       }
    },
    
  },mounted() {
   
   
  }
}
</script>

<style scoped>
  #one {
        background: linear-gradient(
225deg, rgba(252,86,99,1) 0%, rgba(181,0,29,1) 100%);
    overflow: hidden;
  }

#desing2 {
  width: 80%;
  position: absolute;
    top:-20rem;
    left: -20%;
    overflow: visible;
}

#three {
  background: #FFF200;
}



#Path_1 {
    opacity: 0.1;
    filter: blur(50px);
    fill: rgba(0,0,0,1);
}

#Path_2_v {
    fill: url(#Path_2_v);
}



.Path_1 {
    overflow: visible;
    position: absolute;
width: 50%;
   left:50%;
    top: 6px;
    transform: matrix(1,0,0,1,0,0);
}
.Path_2_v {
    overflow: visible;
    position: absolute;
    width: 34%;
    left: 32%;
    top: 23%;
    transform: matrix(1,0,0,1,0,0);
}
</style>

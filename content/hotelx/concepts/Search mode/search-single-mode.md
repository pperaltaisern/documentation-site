+++
title = "Search Single Mode"
pagetitle = "Search, Quote and Book"
description = "Learn about Transactional Booking flow. Search, Quote and Confirm Reservation"
weight = 3
alwaysopen = false
+++

[Search](#search), [Quote](#quote) and [Book](#book) transactions must be executed sequentally in order to book hotel rooms in a Seller.

Performs an hotel availability search over 1 or more [Seller accesses](/admin/resources/common-resources/#accesses)

Depending Seller, search operations implitiy use supplier's cache.

## Search Single Mode
<svg class="search_single_mode" width="504px" height="272px" viewBox="59 83 504 272" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <defs>
        <linearGradient x1="100%" y1="50%" x2="0%" y2="50%" id="Gradient-1">
            <stop stop-color="#0B9FAA" offset="0%"></stop>
            <stop stop-color="#0884BA" offset="57.0874023%"></stop>
            <stop stop-color="#0562CE" offset="100%"></stop>
        </linearGradient>
        <linearGradient x1="2.25097656%" y1="49.999848%" x2="100%" y2="49.999848%" id="Gradient-2">
            <stop stop-color="#0B9FAA" offset="0%"></stop>
            <stop stop-color="#0EB79B" offset="21.4613749%"></stop>
            <stop stop-color="#1D6986" offset="100%"></stop>
        </linearGradient>
        <linearGradient x1="7.7291646%" y1="49.9998493%" x2="92.3039729%" y2="49.9998493%" id="Gradient-3">
            <stop stop-color="#1D6986" offset="0%"></stop>
            <stop stop-color="#33006A" offset="100%"></stop>
        </linearGradient>
    </defs>
    <g id="Group-14" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" transform="translate(60.000000, 85.000000)">
        <g id="Group-4">
            <g id="shutterstock_579153223-[Converted].eps">
                <g id="Group">
                    <g id="Layer_2"></g>
                </g>
            </g>
        </g>
        <text id="SUPPLIER" font-family="Lato-Bold, Lato" font-size="15" font-weight="bold" fill="#182945">
            <tspan x="399" y="267">SUPPLIER</tspan>
        </text>
        <g id="Group-3" transform="translate(224.000000, 38.000000)" fill="#B7C7CF" stroke="#B7C7CF">
            <g id="noun_1437885_cc-(1)">
                <g id="Group">
                    <g id="Group-2" transform="translate(8.000000, 0.000000)" stroke-width="0.2">
                        <path d="M17.9927567,6.72849649 L17.0900688,9.75425459 C17.0211074,9.98741129 17.1546097,10.2320059 17.3880177,10.301513 C17.5268248,10.3428653 17.6762413,10.3129508 17.7894088,10.2232075 L20.0907767,8.39490703 L22.4001016,10.2240873 C22.5910718,10.3754192 22.8695701,10.3437451 23.0216389,10.1537004 C23.1118193,10.0410813 23.1409953,9.8915091 23.0994416,9.75337475 L22.1905649,6.72849649 L24.5476324,4.87380092 C24.7394867,4.72334886 24.7713151,4.44620033 24.6201303,4.25615562 C24.5361388,4.15057523 24.4079412,4.08898666 24.2726706,4.08898666 L21.4028128,4.09602536 L20.516039,1.10106154 C20.4603394,0.911016832 20.2835151,0.782560687 20.0845878,0.785200197 L20.0845878,0.785200197 C19.8909653,0.788719544 19.7220981,0.916295852 19.6672826,1.10106154 L18.7805088,4.09602536 L15.9186081,4.08898666 C15.6745906,4.08898666 15.4765474,4.28519023 15.4756633,4.52802513 C15.4756633,4.66264013 15.5366676,4.7893366 15.6427622,4.87292108 L17.9927567,6.72849649 Z M19.1102861,4.97586196 C19.306561,4.97586196 19.4798488,4.84740582 19.5355485,4.66000062 L20.0916608,2.78154946 L20.6477731,4.66000062 C20.7034728,4.84740582 20.8767606,4.97586196 21.0730355,4.97586196 L22.9977677,4.97146278 L21.4072334,6.22347028 C21.2648898,6.33520953 21.2056537,6.52173489 21.2578169,6.6950627 L21.849294,8.66237736 L20.3675067,7.48867532 C20.2065966,7.36109901 19.9776091,7.36109901 19.8166991,7.48867532 L18.3393323,8.66149752 L18.9263889,6.69330303 C18.9776679,6.52085505 18.9184318,6.33520953 18.7769724,6.22347028 L17.1908587,4.97146278 L19.1102861,4.97586196 Z" id="Shape"></path>
                        <path d="M3.33278649,11.0242711 L2.4300986,14.0500292 C2.36113714,14.2831859 2.49463946,14.5277805 2.72804749,14.5972876 C2.86685454,14.6386399 3.01627105,14.6087255 3.12943858,14.5189821 L5.43080644,12.6906817 L7.74013139,14.519862 C7.9311016,14.6711939 8.20959982,14.6395198 8.36166869,14.4494751 C8.45184907,14.336856 8.48102507,14.1872837 8.43947137,14.0491494 L7.53059463,11.0242711 L9.88766213,9.16957557 C10.0795165,9.01912351 10.1113448,8.74197497 9.96016008,8.55193027 C9.87616855,8.44634987 9.74797096,8.38476131 9.61270039,8.38476131 L6.74284251,8.3918 L5.85606881,5.39683619 C5.80036916,5.20679148 5.62354489,5.07833534 5.42461759,5.08097485 L5.42461759,5.08097485 C5.23099502,5.08449419 5.06212784,5.2120705 5.00731232,5.39683619 L4.12053861,8.3918 L1.25863782,8.38476131 C1.01462033,8.38476131 0.816577149,8.58096487 0.815693027,8.82379978 C0.815693027,8.95841478 0.8766974,9.08511125 0.982791961,9.16869573 L3.33278649,11.0242711 Z M4.45031587,9.27163661 C4.64659081,9.27163661 4.81987859,9.14318047 4.87557824,8.95577527 L5.43169056,7.07732411 L5.98780289,8.95577527 C6.04350253,9.14318047 6.21679031,9.27163661 6.41306525,9.27163661 L8.33779742,9.26723743 L6.74726312,10.5192449 C6.60491958,10.6309842 6.54568345,10.8175095 6.59784661,10.9908373 L7.18932379,12.958152 L5.70753642,11.78445 C5.54662634,11.6568737 5.31763891,11.6568737 5.15672882,11.78445 L3.67936206,12.9572722 L4.26641863,10.9890777 C4.31769767,10.8166297 4.25846154,10.6309842 4.11700212,10.5192449 L2.53088843,9.26723743 L4.45031587,9.27163661 Z" id="Shape"></path>
                        <path d="M32.652727,11.0242711 L31.7500391,14.0500292 C31.6810776,14.2831859 31.8145799,14.5277805 32.047988,14.5972876 C32.186795,14.6386399 32.3362115,14.6087255 32.4493791,14.5189821 L34.7507469,12.6906817 L37.0600719,14.519862 C37.2510421,14.6711939 37.5295403,14.6395198 37.6816092,14.4494751 C37.7717895,14.336856 37.8009655,14.1872837 37.7594118,14.0491494 L36.8505351,11.0242711 L39.2076026,9.16957557 C39.3994569,9.01912351 39.4312853,8.74197497 39.2801006,8.55193027 C39.196109,8.44634987 39.0679114,8.38476131 38.9326409,8.38476131 L36.062783,8.3918 L35.1760093,5.39683619 C35.1203096,5.20679148 34.9434854,5.07833534 34.7445581,5.08097485 L34.7445581,5.08097485 C34.5509355,5.08449419 34.3820683,5.2120705 34.3272528,5.39683619 L33.4404791,8.3918 L30.5785783,8.38476131 C30.3345608,8.38476131 30.1365176,8.58096487 30.1356335,8.82379978 C30.1356335,8.95841478 30.1966379,9.08511125 30.3027324,9.16869573 L32.652727,11.0242711 Z M33.7702563,9.27163661 C33.9665313,9.27163661 34.1398191,9.14318047 34.1955187,8.95577527 L34.751631,7.07732411 L35.3077434,8.95577527 C35.363443,9.14318047 35.5367308,9.27163661 35.7330057,9.27163661 L37.6577379,9.26723743 L36.0672036,10.5192449 C35.9248601,10.6309842 35.8656239,10.8175095 35.9177871,10.9908373 L36.5092643,12.958152 L35.0274769,11.78445 C34.8665668,11.6568737 34.6375794,11.6568737 34.4766693,11.78445 L32.9993025,12.9572722 L33.5863591,10.9890777 C33.6376381,10.8166297 33.578402,10.6309842 33.4369426,10.5192449 L31.8508289,9.26723743 L33.7702563,9.27163661 Z" id="Shape"></path>
                    </g>
                    <path d="M0.394217687,60.6244507 L11.2825102,60.6244507 C11.5001184,60.6244507 11.6767279,60.4480376 11.6767279,60.2306714 L11.6767279,49.4174906 L27.1552912,49.4174906 L27.1552912,60.2306714 C27.1521374,60.4480376 27.3263816,60.6268134 27.5439898,60.6299636 C27.761598,60.6331138 27.9405728,60.4590634 27.9437265,60.2416972 L27.9437265,60.2306714 L27.9437265,49.4174906 L43.4215014,49.4174906 L43.4215014,60.2306714 C43.4215014,60.4480376 43.5981109,60.6244507 43.815719,60.6244507 L54.7040116,60.6244507 C54.9216197,60.6244507 55.0982293,60.4480376 55.0982293,60.2306714 L55.0982293,17.3937793 C55.0982293,17.1764131 54.9216197,17 54.7040116,17 L0.394217687,17 C0.176609524,17 0,17.1764131 0,17.3937793 L0,60.2314589 C0,60.4488251 0.176609524,60.6244507 0.394217687,60.6244507 Z M0.788435374,17.7875587 L54.3097939,17.7875587 L54.3097939,59.8376796 L44.2099367,59.8376796 L44.2099367,49.0244988 C44.2099367,48.8071326 44.0333272,48.6307195 43.815719,48.6307195 L11.2832986,48.6307195 C11.0656905,48.6307195 10.889081,48.8071326 10.889081,49.0244988 L10.889081,59.8376796 L0.78922381,59.8376796 L0.78922381,17.7875587 L0.788435374,17.7875587 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M41.3715694,42.7506901 L49.1802333,42.7506901 C49.3978415,42.7506901 49.574451,42.574277 49.574451,42.3569108 L49.574451,35.5886315 C49.574451,35.3712653 49.3978415,35.1948521 49.1802333,35.1948521 L41.3715694,35.1948521 C41.1539612,35.1948521 40.9773517,35.3712653 40.9773517,35.5886315 L40.9773517,42.3569108 C40.9773517,42.574277 41.1539612,42.7506901 41.3715694,42.7506901 Z M41.7657871,35.9824108 L48.7860156,35.9824108 L48.7860156,41.9631315 L41.7657871,41.9631315 L41.7657871,35.9824108 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M29.6152095,42.7506901 L37.430181,42.7506901 C37.6477891,42.7506901 37.8243986,42.574277 37.8243986,42.3569108 L37.8243986,35.5886315 C37.8243986,35.3712653 37.6477891,35.1948521 37.430181,35.1948521 L29.6152095,35.1948521 C29.3976014,35.1948521 29.2209918,35.3712653 29.2209918,35.5886315 L29.2209918,42.3569108 C29.2209918,42.574277 29.3976014,42.7506901 29.6152095,42.7506901 Z M30.0094272,35.9824108 L37.0359633,35.9824108 L37.0359633,41.9631315 L30.0094272,41.9631315 L30.0094272,35.9824108 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M17.8131204,42.7506901 L25.6280918,42.7506901 C25.8457,42.7506901 26.0223095,42.574277 26.0223095,42.3569108 L26.0223095,35.5886315 C26.0223095,35.3712653 25.8457,35.1948521 25.6280918,35.1948521 L17.8131204,35.1948521 C17.5955122,35.1948521 17.4189027,35.3712653 17.4189027,35.5886315 L17.4189027,42.3569108 C17.4189027,42.574277 17.5955122,42.7506901 17.8131204,42.7506901 Z M18.2073381,35.9824108 L25.2338741,35.9824108 L25.2338741,41.9631315 L18.2073381,41.9631315 L18.2073381,35.9824108 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M14.2202204,42.3569108 L14.2202204,35.5886315 C14.2202204,35.3712653 14.0436109,35.1948521 13.8260027,35.1948521 L6.01103129,35.1948521 C5.79342313,35.1948521 5.61681361,35.3712653 5.61681361,35.5886315 L5.61681361,42.3569108 C5.61681361,42.574277 5.79342313,42.7506901 6.01103129,42.7506901 L13.8260027,42.7506901 C14.0436109,42.7506901 14.2202204,42.574277 14.2202204,42.3569108 Z M13.431785,41.9631315 L6.40524898,41.9631315 L6.40524898,35.9824108 L13.431785,35.9824108 L13.431785,41.9631315 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M41.3715694,29.3267523 L49.1802333,29.3267523 C49.3978415,29.3267523 49.574451,29.1503392 49.574451,28.932973 L49.574451,22.1654812 C49.574451,21.948115 49.3978415,21.7717019 49.1802333,21.7717019 L41.3715694,21.7717019 C41.1539612,21.7717019 40.9773517,21.948115 40.9773517,22.1654812 L40.9773517,28.9337606 C40.9773517,29.1503392 41.1539612,29.3267523 41.3715694,29.3267523 Z M41.7657871,22.5592606 L48.7860156,22.5592606 L48.7860156,28.5399812 L41.7657871,28.5399812 L41.7657871,22.5592606 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M29.6152095,29.3267523 L37.430181,29.3267523 C37.6477891,29.3267523 37.8243986,29.1503392 37.8243986,28.932973 L37.8243986,22.1654812 C37.8243986,21.948115 37.6477891,21.7717019 37.430181,21.7717019 L29.6152095,21.7717019 C29.3976014,21.7717019 29.2209918,21.948115 29.2209918,22.1654812 L29.2209918,28.9337606 C29.2209918,29.1503392 29.3976014,29.3267523 29.6152095,29.3267523 Z M30.0094272,22.5592606 L37.0359633,22.5592606 L37.0359633,28.5399812 L30.0094272,28.5399812 L30.0094272,22.5592606 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M17.8131204,29.3267523 L25.6280918,29.3267523 C25.8457,29.3267523 26.0223095,29.1503392 26.0223095,28.932973 L26.0223095,22.1654812 C26.0223095,21.948115 25.8457,21.7717019 25.6280918,21.7717019 L17.8131204,21.7717019 C17.5955122,21.7717019 17.4189027,21.948115 17.4189027,22.1654812 L17.4189027,28.9337606 C17.4189027,29.1503392 17.5955122,29.3267523 17.8131204,29.3267523 Z M18.2073381,22.5592606 L25.2338741,22.5592606 L25.2338741,28.5399812 L18.2073381,28.5399812 L18.2073381,22.5592606 Z" id="Shape" stroke-width="0.6"></path>
                    <path d="M6.01024286,29.3267523 L13.8252143,29.3267523 C14.0428224,29.3267523 14.219432,29.1503392 14.219432,28.932973 L14.219432,22.1654812 C14.219432,21.948115 14.0428224,21.7717019 13.8252143,21.7717019 L6.01024286,21.7717019 C5.79263469,21.7717019 5.61602517,21.948115 5.61602517,22.1654812 L5.61602517,28.9337606 C5.61602517,29.1503392 5.79263469,29.3267523 6.01024286,29.3267523 Z M6.40446054,22.5592606 L13.4309966,22.5592606 L13.4309966,28.5399812 L6.40446054,28.5399812 L6.40446054,22.5592606 L6.40446054,22.5592606 Z" id="Shape" stroke-width="0.6"></path>
                </g>
            </g>
        </g>
        <g id="Group" transform="translate(421.000000, 38.000000)" stroke="#B7C7CF" stroke-width="0.3" fill="#B7C7CF">
            <path d="M12.028169,16.1631985 C16.3382629,16.1631985 19.7462441,12.6711495 19.7462441,8.4806906 C19.7462441,4.29023171 16.2380282,0.798182644 12.028169,0.798182644 C7.71807512,0.798182644 4.3100939,4.29023171 4.3100939,8.4806906 C4.3100939,12.6711495 7.71807512,16.1631985 12.028169,16.1631985 Z M12.028169,2.09522944 C15.6366197,2.09522944 18.5434272,4.98864153 18.5434272,8.58046343 C18.5434272,12.1722853 15.6366197,15.0656974 12.028169,15.0656974 C8.41971831,15.0656974 5.5129108,12.1722853 5.5129108,8.58046343 C5.5129108,4.98864153 8.41971831,2.09522944 12.028169,2.09522944 Z" id="Shape"></path>
            <path class="shape-3" d="M16.4384977,17.061154 L12.028169,24.6438891 L7.61784038,17.061154 L0,17.061154 L0,40.9068605 L4.20985915,40.9068605 L4.20985915,60.9611995 L19.6460094,60.9611995 L19.6460094,40.9068605 L24.056338,40.9068605 L24.056338,17.061154 L16.4384977,17.061154 Z M22.7532864,39.7095866 L18.5434272,39.7095866 L18.5434272,59.7639255 L5.5129108,59.7639255 L5.5129108,39.7095866 L1.30305164,39.7095866 L1.30305164,18.258428 L7.01643192,18.258428 L12.1284038,27.0384371 L17.2403756,18.258428 L22.9537559,18.258428 L22.9537559,39.7095866 L22.7532864,39.7095866 Z" id="Shape"></path>
        </g>
        <g id="Group-7" transform="translate(1.000000, 0.000000)">
            <g id="Group-12">
                <g id="Group-13" transform="translate(0.000000, 2.000000)">
                    <path class="circle-one" d="M67,134 C103.886286,134 133.811468,103.34197 134,66.5 C134.000079,66.4845157 134,67.3501673 134,67.3501673 L156.5,67.3501673 L156.5,69.3000031 L160,67.3501673 L156.5,65.4000092 L156.5,67.2850676 L134,67.2850676 C133.776405,30.4721628 103.865229,0 67,0 C29.9969218,0 0,29.9969218 0,67 C0,104.003078 29.9969218,134 67,134 Z" id="Oval-3" stroke="url(#Gradient-1)" stroke-width="3"></path>
                    <rect id="Rectangle" fill="#FFFFFF" x="116" y="68.8500061" width="31" height="15"></rect>
                </g>
                <g id="Group-13" transform="translate(183.000000, 0.000000)">
                    <path class="circle-two" d="M67,136 C103.886286,136 133.811468,105.34197 134,68.5 C134.000079,68.4845157 134,69.3501673 134,69.3501673 L156.5,69.3501673 L156.5,71.3000031 L160,69.3501673 L156.5,67.4000092 L156.5,69.2850676 L134,69.2850676 C133.776405,32.4721628 103.865229,2 67,2 C29.9969218,2 0,31.9969218 0,69 C0,106.003078 29.9969218,136 67,136 Z" id="Oval-3" stroke="url(#linearGradient-2)" stroke-width="3"></path>
                    <rect id="Rectangle" fill="#FFFFFF" x="116" y="70.8500061" width="31" height="15"></rect>
                    <path class="circle-three" d="M250,134 C286.886286,134 316.811468,103.34197 317,66.5 C317.000079,66.4845157 317,67.3501673 317,67.3501673 C316.776405,30.4721628 286.865229,0 250,0 C212.996922,0 183,29.9969218 183,67 C183,104.003078 212.996922,134 250,134 Z" id="Oval-3" stroke="url(#Gradient-3)" stroke-width="3"></path>
                </g>
            </g>
            <path d="M87.9166667,62.8275862 L83.8333333,62.8275862 L83.8333333,60.3957414 C83.8333333,56.374 80.53645,53.1026379 76.4833333,53.1026379 L74.85,53.1026379 L74.85,49.0517241 C74.85,47.7114138 73.7507667,46.6206897 72.4,46.6206897 L62.6,46.6206897 C61.2492333,46.6206897 60.15,47.7114138 60.15,49.0517241 L60.15,53.1026379 L58.5174833,53.1026379 C54.4643667,53.1026379 51.1666667,56.374 51.1666667,60.3957414 L51.1666667,62.8275862 L48.7174833,62.8275862 L48.7174833,51.3676897 C50.1229667,51.0054655 51.1674833,49.747 51.1674833,48.2413793 C51.1674833,46.4537586 49.7023833,45 47.9008167,45 C46.09925,45 44.63415,46.4537586 44.63415,48.2413793 C44.63415,49.747 45.6786667,51.0054655 47.08415,51.3676897 L47.08415,62.8275862 L47.0833333,62.8275862 C44.8317833,62.8275862 43,64.6451897 43,66.8793103 L43,73.3612586 C43,75.5961897 44.8317833,77.4137931 47.0833333,77.4137931 L51.1666667,77.4137931 L51.1666667,85.5172414 L45.45,85.5172414 C44.9983833,85.5172414 44.6333333,85.8794655 44.6333333,86.3275862 L44.6333333,91.1896552 C44.6333333,91.6377759 44.9983833,92 45.45,92 L89.55,92 C90.0016167,92 90.3666667,91.6377759 90.3666667,91.1896552 L90.3666667,86.3275862 C90.3666667,85.8794655 90.0016167,85.5172414 89.55,85.5172414 L83.8333333,85.5172414 L83.8333333,77.4137931 L87.9166667,77.4137931 C90.1682167,77.4137931 92,75.5961897 92,73.3612586 L92,66.8793103 C92,64.6451897 90.1682167,62.8275862 87.9166667,62.8275862 Z M61.7833333,49.0517241 C61.7833333,48.6044138 62.1492,48.2413793 62.6,48.2413793 L72.4,48.2413793 C72.8508,48.2413793 73.2166667,48.6044138 73.2166667,49.0517241 L73.2166667,53.1026379 L61.7833333,53.1026379 L61.7833333,49.0517241 Z M52.8,76.6075 C52.8,76.6058793 52.8008167,76.605069 52.8008167,76.6034483 C52.8008167,76.6018276 52.8,76.6010172 52.8,76.5993966 L52.8,63.6419828 C52.8,63.6403621 52.8008167,63.6395517 52.8008167,63.637931 C52.8008167,63.6363103 52.8,63.6355 52.8,63.6338793 L52.8,60.3957414 C52.8,57.2686207 55.36515,54.7233276 58.5174833,54.7233276 L60.9625833,54.7233276 C60.9642167,54.7233276 60.9650333,54.7241379 60.9666667,54.7241379 L74.0333333,54.7241379 C74.0349667,54.7241379 74.0357833,54.7233276 74.0374167,54.7233276 L76.4833333,54.7233276 C79.63485,54.7233276 82.2,57.2686207 82.2,60.3957414 L82.2,80.6551724 L52.8,80.6551724 L52.8,76.6075 Z M52.8,82.2758621 L82.2,82.2758621 L82.2,85.5172414 L52.8,85.5172414 L52.8,82.2758621 Z M46.2674833,48.2413793 C46.2674833,47.347569 47.0000333,46.6206897 47.9008167,46.6206897 C48.8016,46.6206897 49.53415,47.347569 49.53415,48.2413793 C49.53415,49.1351897 48.8016,49.862069 47.9008167,49.862069 C47.0000333,49.862069 46.2674833,49.1351897 46.2674833,48.2413793 Z M47.0833333,75.7931034 C45.7325667,75.7931034 44.6333333,74.701569 44.6333333,73.3612586 L44.6333333,66.8793103 C44.6333333,65.539 45.7325667,64.4482759 47.0833333,64.4482759 L51.1666667,64.4482759 L51.1666667,75.7931034 L47.0833333,75.7931034 Z M88.7333333,87.137931 L88.7333333,90.3793103 L46.2666667,90.3793103 L46.2666667,87.137931 L88.7333333,87.137931 Z M90.3666667,73.3612586 C90.3666667,74.701569 89.2674333,75.7931034 87.9166667,75.7931034 L83.8333333,75.7931034 L83.8333333,64.4482759 L87.9166667,64.4482759 C89.2674333,64.4482759 90.3666667,65.539 90.3666667,66.8793103 L90.3666667,73.3612586 Z M65.05,64.4490862 C65.05,61.7676552 62.85235,59.5862069 60.15,59.5862069 C57.44765,59.5862069 55.25,61.7676552 55.25,64.4490862 C55.25,67.1297069 57.44765,69.3103448 60.15,69.3103448 C62.85235,69.3103448 65.05,67.1297069 65.05,64.4490862 Z M56.8833333,64.4490862 C56.8833333,62.6614655 58.3484333,61.2068966 60.15,61.2068966 C61.9515667,61.2068966 63.4166667,62.6614655 63.4166667,64.4490862 C63.4166667,66.2358966 61.9515667,67.6896552 60.15,67.6896552 C58.3484333,67.6896552 56.8833333,66.2358966 56.8833333,64.4490862 Z M74.85,59.5862069 C72.14765,59.5862069 69.95,61.7676552 69.95,64.4490862 C69.95,67.1297069 72.14765,69.3103448 74.85,69.3103448 C77.55235,69.3103448 79.75,67.1297069 79.75,64.4490862 C79.75,61.7676552 77.55235,59.5862069 74.85,59.5862069 Z M74.85,67.6896552 C73.0484333,67.6896552 71.5833333,66.2358966 71.5833333,64.4490862 C71.5833333,62.6614655 73.0484333,61.2068966 74.85,61.2068966 C76.6515667,61.2068966 78.1166667,62.6614655 78.1166667,64.4490862 C78.1166667,66.2358966 76.6515667,67.6896552 74.85,67.6896552 Z M75.6666667,73.362069 L59.3333333,73.362069 C57.9825667,73.362069 56.8833333,74.4527931 56.8833333,75.7931034 L56.8833333,76.6034483 C56.8833333,77.9437586 57.9825667,79.0344828 59.3333333,79.0344828 L75.6666667,79.0344828 C77.0174333,79.0344828 78.1166667,77.9437586 78.1166667,76.6034483 L78.1166667,75.7931034 C78.1166667,74.4527931 77.0174333,73.362069 75.6666667,73.362069 Z M76.4833333,76.6034483 C76.4833333,77.0507586 76.1174667,77.4137931 75.6666667,77.4137931 L59.3333333,77.4137931 C58.8825333,77.4137931 58.5166667,77.0507586 58.5166667,76.6034483 L58.5166667,75.7931034 C58.5166667,75.3457931 58.8825333,74.9827586 59.3333333,74.9827586 L75.6666667,74.9827586 C76.1174667,74.9827586 76.4833333,75.3457931 76.4833333,75.7931034 L76.4833333,76.6034483 Z" id="Shape" fill="#B7C7CF"></path>
        </g>
        <g id="Group-11" transform="translate(28.000000, 148.000000)">
            <text id="CUSTOMER" font-family="Lato-Bold, Lato" font-size="15" font-weight="bold" fill="#182945">
                <tspan x="0" y="119">CUSTOMER</tspan>
            </text>
            <g id="Group-6" transform="translate(35.000000, 0.000000)" fill="#0562CE">
                <g id="XMLID_32_" transform="translate(4.605611, 0.128213)">
                    <rect id="XMLID_61_" x="0.00778565458" y="0.655866701" width="3.31119677" height="74.9866239"></rect>
                </g>
                <g id="XMLID_41_" transform="translate(0.019864, 72.333721)">
                    <path d="M6.24913136,11.9247397 C3.00054631,11.9247397 0.358813323,9.28442496 0.358813323,6.03758393 C0.358813323,2.7907429 3.00054631,0.150428143 6.24913136,0.150428143 C9.49651235,0.150428143 12.1382453,2.7907429 12.1382453,6.03758393 C12.1382453,9.28442496 9.49651235,11.9247397 6.24913136,11.9247397 Z M6.24913136,3.46225413 C4.82712286,3.46225413 3.67121417,4.61754226 3.67121417,6.03878735 C3.67121417,7.46003244 4.82712286,8.61532058 6.24913136,8.61532058 C7.6699358,8.61532058 8.82584449,7.46003244 8.82584449,6.03878735 C8.82584449,4.61754226 7.67113987,3.46225413 6.24913136,3.46225413 Z" id="XMLID_43_"></path>
                </g>
            </g>
        </g>
        <rect id="XMLID_61_" fill="#09909F" x="250.613397" y="148.78408" width="3.31119677" height="74.9866239"></rect>
        <path d="M252.268995,232.258461 C249.02041,232.258461 246.378677,229.618146 246.378677,226.371305 C246.378677,223.124464 249.02041,220.484149 252.268995,220.484149 C255.516376,220.484149 258.158109,223.124464 258.158109,226.371305 C258.158109,229.618146 255.516376,232.258461 252.268995,232.258461 Z M252.268995,223.795975 C250.846987,223.795975 249.691078,224.951264 249.691078,226.372509 C249.691078,227.793754 250.846987,228.949042 252.268995,228.949042 C253.6898,228.949042 254.845708,227.793754 254.845708,226.372509 C254.845708,224.951264 253.691004,223.795975 252.268995,223.795975 Z" id="XMLID_43_" fill="#09909F"></path>
        <rect id="XMLID_61_" fill="#33006A" x="430.613397" y="148.78408" width="3.31119677" height="74.9866239"></rect>
        <path d="M432.268995,232.258461 C429.02041,232.258461 426.378677,229.618146 426.378677,226.371305 C426.378677,223.124464 429.02041,220.484149 432.268995,220.484149 C435.516376,220.484149 438.158109,223.124464 438.158109,226.371305 C438.158109,229.618146 435.516376,232.258461 432.268995,232.258461 Z M432.268995,223.795975 C430.846987,223.795975 429.691078,224.951264 429.691078,226.372509 C429.691078,227.793754 430.846987,228.949042 432.268995,228.949042 C433.6898,228.949042 434.845708,227.793754 434.845708,226.372509 C434.845708,224.951264 433.691004,223.795975 432.268995,223.795975 Z" id="XMLID_43_" fill="#33006A"></path>
        <text id="HOTELX" font-family="Lato-Heavy, Lato" font-size="18" font-weight="600" fill="#182945">
            <tspan x="217" y="266">HOTELX</tspan>
        </text>
        <g id="Group-6" transform="translate(246.000000, 148.000000)">
            <g id="XMLID_32_" transform="translate(4.605611, 0.128213)"></g>
            <g id="XMLID_41_" transform="translate(0.019864, 72.333721)"></g>
        </g>
        <g id="Group-6" transform="translate(426.000000, 148.000000)">
            <g id="XMLID_32_" transform="translate(4.605611, 0.128213)"></g>
            <g id="XMLID_41_" transform="translate(0.019864, 72.333721)"></g>
        </g>
    </g>
</svg>




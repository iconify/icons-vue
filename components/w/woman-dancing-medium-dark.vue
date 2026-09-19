<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ij8aQzc)"><path fill="url(#ipZYa6k)" class="a-zqzeldx"/><path fill="url(#iqZUvHG)" class="a-zqzeldx"/></g><path fill="url(#i4Wc1Fe)" class="uwqjkbvol"/><path fill="url(#imd4NIb)" class="uwqjkbvol"/><path fill="url(#i1Vpllf)" class="uwqjkbvol"/><g filter="url(#imNrHCc)"><path class="a9-b904md"/></g><g filter="url(#i9tGrBe)"><path class="u8l8bnbbx"/></g><path fill="url(#iehuA5b)" class="ifk4wkbgx"/><path fill="url(#ipA3SbU)" class="ifk4wkbgx"/><path fill="url(#i1ynvbt)" class="a2ysf6bzt"/><g filter="url(#isWRH5b)"><path class="fkpcsjb3b"/><path fill="url(#isG3bdd)" class="o5cnyqbgj"/><path fill="url(#iaYEDqZ)" class="o5cnyqbgj"/></g><g filter="url(#iBu68wE)"><path fill="url(#iLuyZJb)" class="e648o_baz"/><path fill="url(#ikP0P5c)" class="e648o_baz"/><path fill="url(#iLMCzNd)" class="e648o_baz"/><path fill="url(#i8uPQSc)" class="e648o_baz"/><path fill="url(#i4DOhAc)" class="e648o_baz"/></g><g filter="url(#icLE4bl)"><path fill="url(#i9huZKN)" class="d49vq-b3b"/><path fill="url(#i60rmed)" class="d49vq-b3b"/><path fill="url(#i3wkpUc)" class="d49vq-b3b"/></g><path fill="url(#iW7Dhmc)" class="d49vq-b3b"/><path fill="url(#iLbqbCd)" class="d49vq-b3b"/><g filter="url(#iACK5ac)"><path class="v9xkymirg"/></g><g filter="url(#iRhovkd)"><path class="futtttqqr"/><path fill="url(#iiLckWc)" class="bds0mc2jk"/></g><path fill="url(#iH2ZIwj)" class="ws5-tkbbq"/><path fill="url(#iBTREUc)" class="ws5-tkbbq"/><g filter="url(#ikIaggd)"><path fill="url(#iJyVWnb)" class="f-1fthf3z"/></g><path fill="url(#i5azuEO)" class="e7x_umu1z"/><g filter="url(#i723Hyc)"><path fill="url(#iWVRYHd)" class="bgcikgb_z"/></g><g filter="url(#i2YIVAc)"><path fill="url(#iLGdf6c)" class="f4zah8e_v"/></g><g filter="url(#iW25Qje)"><path fill="url(#i80ZzQd)" class="gc5jyu-5m"/></g><path fill="url(#irGKDxe)" class="gc5jyu-5m"/><path fill="url(#iYI99Ac)" class="gc5jyu-5m"/><path fill="url(#iiDwZtb)" class="gc5jyu-5m"/><path fill="url(#iXuQcSb)" class="gc5jyu-5m"/><g filter="url(#iWJsrqc)"><path class="mgek_kbvl"/></g><path class="d7eg-abyg"/><path fill="url(#i8qeySc)" class="dvmh07mfm"/><path fill="url(#i7mbzWc)" class="dvmh07mfm"/><path fill="url(#i49AU3c)" class="dvmh07mfm"/><path fill="url(#i1kaq8d)" class="dvmh07mfm"/><path fill="url(#iMKyd2Z)" class="dvmh07mfm"/><g filter="url(#iRATohe)"><path stroke="url(#irsebVc)" class="pk_7ilbgy"/></g><path class="v00lg4c1x"/><g filter="url(#iSMpgrc)"><path class="bx8w24b7x"/></g><g filter="url(#ivbaagN)"><path class="zdnvr8b2y"/></g><g filter="url(#iP3SREs)"><path fill="url(#iYS2gKr)" class="m472w0fxa"/></g><g filter="url(#iFWuDcd)"><path fill="url(#i33vZKb)" clip-rule="evenodd" class="vwva7zb6f"/></g><path class="galfynzfj"/><path fill="url(#iEgq0rd)" class="i_adio88s"/><path class="idx3obcoi"/><g filter="url(#i7yrS6c)"><path class="p7beq2bgt"/><path fill="url(#i9W19jb)" class="gojf2jtsr"/></g><g filter="url(#iyvjUab)"><path fill="url(#iexauib)" class="mudzph12f"/></g><path class="r7_ojkbmv"/><path fill="url(#iXdBk2d)" class="njr-tqk5i"/><path class="pfi2macjv"/><g filter="url(#i0jNKwb)"><path fill="url(#i3N10Zd)" class="gq7r-y_jo"/></g><g filter="url(#iwkCHTb)"><ellipse transform="rotate(-27.914 11.197 5.792)" class="e_534j-zv"/><ellipse fill="url(#iBvTIGg)" transform="rotate(-27.914 11.197 5.792)" class="rhhoifucn"/></g><g filter="url(#iIY342c)"><path class="p_c4y8b-n"/></g><g filter="url(#iQ0O0Rb)"><path class="y95rwebpc"/></g><g filter="url(#iWCL6Zc)"><path fill="url(#inEv8xb)" class="o1_zjo1ay"/></g><g filter="url(#iOC8d1b)"><path fill="url(#izjUp2b)" class="rttxvnbop"/></g><g filter="url(#iMWlZOd)"><path fill="url(#iyIEygP)" class="rttxvnbop"/><path fill="url(#ilSJSze)" class="rttxvnbop"/></g><g filter="url(#iZENx2c)"><path fill="url(#iaPypic)" clip-rule="evenodd" class="kkds9sbif"/></g><g filter="url(#iFEDwzc)"><path fill="url(#iJGx8Rc)" clip-rule="evenodd" class="ga74agm1p"/></g><defs><radialGradient id="ipZYa6k" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0221 3.32904 -7.39612 -4.4925 15.157 2.99)" gradientUnits="userSpaceOnUse"><stop class="dbrr_ge-k"/><stop offset="1" class="whopo0y2h"/></radialGradient><radialGradient id="iqZUvHG" cx="0" cy="0" r="1" gradientTransform="rotate(167.39 7.744 4.93)scale(1.39146 1.55201)" gradientUnits="userSpaceOnUse"><stop class="f88wzbb7k"/><stop offset="1" class="w4rlmo2dn"/></radialGradient><radialGradient id="i1Vpllf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72861 4.02946 -1.91414 -.82115 8.63 27.856)" gradientUnits="userSpaceOnUse"><stop class="rxdm1gb4b"/><stop offset="1" class="en9rkbb0o"/></radialGradient><radialGradient id="i1ynvbt" cx="0" cy="0" r="1" gradientTransform="rotate(117.071 -3.416 17.085)scale(2.08793 1.98277)" gradientUnits="userSpaceOnUse"><stop class="u6ezkbbkd"/><stop offset="1" class="cpmw12bkg"/></radialGradient><radialGradient id="isG3bdd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.07276 -1.17167 0 20.377 7.221)" gradientUnits="userSpaceOnUse"><stop class="pjtqv3e9z"/><stop offset="1" class="ivwd4jbev"/></radialGradient><radialGradient id="iaYEDqZ" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 9.82 4.868)scale(.67604 .47453)" gradientUnits="userSpaceOnUse"><stop class="d_b_m49gm"/><stop offset="1" class="tk4_g-b3s"/></radialGradient><radialGradient id="iLuyZJb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.18747 -5.71878 5.09832 -4.62466 15.278 14.836)" gradientUnits="userSpaceOnUse"><stop class="zstr-2b3h"/><stop offset="1" class="r38-lhbhs"/></radialGradient><radialGradient id="ikP0P5c" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -.45703 .8012 5.4783 9.84 12.324)" gradientUnits="userSpaceOnUse"><stop offset=".481" class="dz8dqqbnh"/><stop offset="1" class="hv09-7aho"/></radialGradient><radialGradient id="iLMCzNd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4375 0 0 -4.28125 16.153 9.867)" gradientUnits="userSpaceOnUse"><stop offset=".144" class="d1nygi1_s"/><stop offset="1" class="bzjd0s3dz"/></radialGradient><radialGradient id="i8uPQSc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.14245 .25001 -.22815 -1.9551 15.952 12.71)" gradientUnits="userSpaceOnUse"><stop class="etzb8g0rx"/><stop offset="1" class="q_d1lub6r"/></radialGradient><radialGradient id="i4DOhAc" cx="0" cy="0" r="1" gradientTransform="rotate(91.112 2.088 9.266)scale(2.8878 5.12554)" gradientUnits="userSpaceOnUse"><stop class="ed0bwz-2w"/><stop offset="1" class="h1j4vebkc"/></radialGradient><radialGradient id="i9huZKN" cx="0" cy="0" r="1" gradientTransform="rotate(45.496 -14.752 21.43)scale(10.2092 15.8767)" gradientUnits="userSpaceOnUse"><stop class="h84ffkb2i"/><stop offset="1" class="emq3pu1ym"/></radialGradient><radialGradient id="i3wkpUc" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -4.4375 3.8181 .75287 27.06 16.648)" gradientUnits="userSpaceOnUse"><stop offset=".37" class="c4hclxboa"/><stop offset="1" class="mz51gmfzq"/></radialGradient><radialGradient id="iW7Dhmc" cx="0" cy="0" r="1" gradientTransform="matrix(4.72488 -2.8426 6.67598 11.09657 4.788 29.252)" gradientUnits="userSpaceOnUse"><stop class="ket8l8b0j"/><stop offset="1" class="lze6x5b3f"/></radialGradient><radialGradient id="iLbqbCd" cx="0" cy="0" r="1" gradientTransform="matrix(.81156 -4.64805 2.43505 .42516 28.216 17.497)" gradientUnits="userSpaceOnUse"><stop class="m8u-j2bfh"/><stop offset="1" class="xbj9zzvwg"/></radialGradient><radialGradient id="iiLckWc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.31249 1.60939 -.35465 -.72996 11.236 9.283)" gradientUnits="userSpaceOnUse"><stop offset=".163" class="nwegx7xkg"/><stop offset="1" class="a1xx86brr"/></radialGradient><radialGradient id="iH2ZIwj" cx="0" cy="0" r="1" gradientTransform="matrix(-.80887 -1.87683 2.42187 -1.04377 13.58 10.361)" gradientUnits="userSpaceOnUse"><stop class="cz3brismi"/><stop offset="1" class="cgagdkbfp"/></radialGradient><radialGradient id="iBTREUc" cx="0" cy="0" r="1" gradientTransform="rotate(47.291 -3.816 17.657)scale(1.79682 5.00055)" gradientUnits="userSpaceOnUse"><stop class="y9u9iibtz"/><stop offset="1" class="ebrwadt3p"/></radialGradient><radialGradient id="i5azuEO" cx="0" cy="0" r="1" gradientTransform="matrix(-.52402 .51786 -.35536 -.3596 15.152 5.788)" gradientUnits="userSpaceOnUse"><stop class="kv4_lccbf"/><stop offset="1" class="a0kmoyxfg"/></radialGradient><radialGradient id="iWVRYHd" cx="0" cy="0" r="1" gradientTransform="rotate(90 4.239 10.354)scale(.50089)" gradientUnits="userSpaceOnUse"><stop class="kn22s4txk"/><stop offset="1" class="y4inpcddo"/></radialGradient><radialGradient id="iLGdf6c" cx="0" cy="0" r="1" gradientTransform="rotate(106.949 2.778 6.694)scale(.67671)" gradientUnits="userSpaceOnUse"><stop offset=".342" class="h9hedgb-i"/><stop offset="1" class="fcfe9dfwi"/></radialGradient><radialGradient id="i80ZzQd" cx="0" cy="0" r="1" gradientTransform="rotate(150.368 5.788 4.935)scale(2.75189 3.83954)" gradientUnits="userSpaceOnUse"><stop class="t-07fdchd"/><stop offset="1" class="jk372--tq"/></radialGradient><radialGradient id="irGKDxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.54276 -4.67289 0 12.342 5.357)" gradientUnits="userSpaceOnUse"><stop offset=".658" class="s3-919bdo"/><stop offset=".999" class="zrq_ottju"/></radialGradient><radialGradient id="iYI99Ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.93706 .6165 -.98106 -1.49119 14.418 4.493)" gradientUnits="userSpaceOnUse"><stop class="q6mg8ibon"/><stop offset="1" class="m4wre3b4e"/></radialGradient><radialGradient id="iiDwZtb" cx="0" cy="0" r="1" gradientTransform="matrix(.39455 .41921 -1.6032 1.50891 10.867 3.95)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="y6gj-0bkn"/><stop offset="1" class="ta7v5vpcw"/></radialGradient><radialGradient id="iXuQcSb" cx="0" cy="0" r="1" gradientTransform="rotate(134.662 5.878 5.101)scale(1.94071 1.24456)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="gr1si2b-x"/><stop offset="1" class="s0bi7iy1o"/></radialGradient><radialGradient id="i7mbzWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.37606 0 0 -.11752 12.538 6.817)" gradientUnits="userSpaceOnUse"><stop class="cn11jacls"/><stop offset="1" class="mkrjvhq2k"/></radialGradient><radialGradient id="i49AU3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.30983 .82485 0 12.342 7.066)" gradientUnits="userSpaceOnUse"><stop offset=".244" class="chywufrfu"/><stop offset="1" class="u7harwjoq"/></radialGradient><radialGradient id="iEgq0rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.24811 .35977 -.57071 -.39359 13.607 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="i9W19jb" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 8.065 -.307)scale(.17566 .24183)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXdBk2d" cx="0" cy="0" r="1" gradientTransform="matrix(-.24812 .35977 -.57072 -.3936 11.573 5.78)" gradientUnits="userSpaceOnUse"><stop offset=".622" class="chm_zob8h"/><stop offset="1" class="w_bi9zfnz"/></radialGradient><radialGradient id="iBvTIGg" cx="0" cy="0" r="1" gradientTransform="matrix(-.0036 -.22942 .27577 -.00432 11.19 5.939)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="inEv8xb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56588 1.26997 -.49095 -.60535 10.904 3.643)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="dgweptk-f"/><stop offset=".77" class="nhe36etun"/></radialGradient><radialGradient id="izjUp2b" cx="0" cy="0" r="1" gradientTransform="rotate(178.548 7.075 1.931)scale(2.7381 1.32767)" gradientUnits="userSpaceOnUse"><stop class="p224_4b9x"/><stop offset="1" class="umf8cbcnm"/></radialGradient><radialGradient id="iyIEygP" cx="0" cy="0" r="1" gradientTransform="matrix(.3329 -2.30567 5.0715 .73225 11.62 4.629)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="rlatyn0wa"/><stop offset="1" class="x_nmsobjl"/></radialGradient><radialGradient id="ilSJSze" cx="0" cy="0" r="1" gradientTransform="rotate(-169.129 7.392 1.433)scale(1.89583 .54016)" gradientUnits="userSpaceOnUse"><stop offset=".226" class="xz2vy3rji"/><stop offset="1" class="bw1rz3b-f"/></radialGradient><filter id="ij8aQzc" width="11.621" height="12.177" x="4.756" y="1.586" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.184314 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="imNrHCc" width="6.401" height="8.773" x="16.966" y="21.109" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.262745 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="i9tGrBe" width="4.034" height="2.448" x="19.082" y="27.435" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.1"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.219608 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="isWRH5b" width="8.253" height="7.777" x="14.731" y="2.934" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.223529 0 0 0 0 0.396078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_612" result="effect2_innerShadow_4002_612"/></filter><filter id="iBu68wE" width="7.93" height="8.273" x="9.022" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.741176 0 0 0 0 0.207843 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="icLE4bl" width="24.323" height="17.206" x="4.092" y="13.208" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.27451 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.2 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_612" result="effect2_innerShadow_4002_612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.141176 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_612" result="effect3_innerShadow_4002_612"/></filter><filter id="iACK5ac" width="2.218" height="2.723" x="4.114" y="15.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.145098 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="iRhovkd" width="7.274" height="8.998" x="3.684" y="8.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.27451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.266667 0 0 0 0 0.360784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_612" result="effect2_innerShadow_4002_612"/></filter><filter id="ikIaggd" width="1.601" height="1.501" x="9.407" y="5.365" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.368627 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="i723Hyc" width="1.402" height="1.402" x="13.892" y="5.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".1"/></filter><filter id="i2YIVAc" width="1.202" height="1.202" x="9.565" y="5.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iW25Qje" width="5.152" height="5.072" x="9.966" y="3.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.521569 0 0 0 0 0.380392 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="iWJsrqc" width="1.375" height="1.751" x="11.579" y="5.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".125"/></filter><filter id="iRATohe" width="1.74" height=".725" x="11.472" y="7.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".025"/></filter><filter id="iSMpgrc" width="1.506" height=".599" x="12.675" y="5.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.0862745 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="ivbaagN" width="1.506" height=".599" x="10.503" y="5.46" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0784314 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="iP3SREs" width="1.251" height=".615" x="10.566" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="iFWuDcd" width="1.251" height=".616" x="13.092" y="4.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0431373 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/></filter><filter id="i7yrS6c" width=".472" height=".43" x="12.964" y="5.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iyvjUab" width=".628" height=".638" x="13.302" y="5.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".1"/></filter><filter id="i0jNKwb" width=".672" height=".697" x="11.23" y="5.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".1"/></filter><filter id="iwkCHTb" width=".531" height=".434" x="10.932" y="5.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iIY342c" width="1.024" height=".426" x="13.122" y="4.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iQ0O0Rb" width="1.024" height=".426" x="10.579" y="4.868" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iWCL6Zc" width="1.749" height="2.018" x="9.539" y="2.995" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iOC8d1b" width="4.106" height="2.95" x="10.672" y="2.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.0823529 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/><feGaussianBlur result="effect2_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iMWlZOd" width="4.106" height="2.8" x="10.672" y="2.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_612" stdDeviation=".05"/></filter><filter id="iZENx2c" width="2.957" height="3.037" x="12.949" y="2.439" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.341176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.247059 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_612" result="effect2_innerShadow_4002_612"/></filter><filter id="iFEDwzc" width="1.893" height="1.933" x="13.445" y="3.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.266667 0 0 0 0 0.345098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_612"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.0627451 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_612" result="effect2_innerShadow_4002_612"/></filter><linearGradient id="i4Wc1Fe" x1="21.631" x2="12.192" y1="20.756" y2="31.059" gradientUnits="userSpaceOnUse"><stop class="x_atgxb_v"/><stop offset="1" class="ppa6_abwh"/></linearGradient><linearGradient id="imd4NIb" x1="9.974" x2="19.537" y1="24.594" y2="28.553" gradientUnits="userSpaceOnUse"><stop class="yung1xdgy"/><stop offset="1" class="i-td5rxsk"/></linearGradient><linearGradient id="iehuA5b" x1="11.126" x2="8.785" y1="27.476" y2="26.934" gradientUnits="userSpaceOnUse"><stop class="yhc7rmbsi"/><stop offset="1" class="lqgx_abdw"/></linearGradient><linearGradient id="ipA3SbU" x1="8.408" x2="8.908" y1="27.377" y2="27.659" gradientUnits="userSpaceOnUse"><stop offset=".221" class="v2w0c2b8h"/><stop offset="1" class="ffknxknmx"/></linearGradient><linearGradient id="i60rmed" x1="28.216" x2="16.204" y1="17.367" y2="17.367" gradientUnits="userSpaceOnUse"><stop offset=".219" class="k2sx12b0p"/><stop offset="1" class="yu3j8mbni"/></linearGradient><linearGradient id="iJyVWnb" x1="9.69" x2="10.157" y1="5.899" y2="6.866" gradientUnits="userSpaceOnUse"><stop class="e-084nbmr"/><stop offset="1" class="sh2s77xqm"/></linearGradient><linearGradient id="i8qeySc" x1="12.68" x2="12.31" y1="6.546" y2="6.565" gradientUnits="userSpaceOnUse"><stop class="raocb-buh"/><stop offset="1" class="jcz4yrb9y"/></linearGradient><linearGradient id="i1kaq8d" x1="12.375" x2="12.375" y1="7.089" y2="6.947" gradientUnits="userSpaceOnUse"><stop class="ouau4qbku"/><stop offset="1" class="er3a68ttw"/></linearGradient><linearGradient id="iMKyd2Z" x1="12.342" x2="12.342" y1="5.815" y2="6.552" gradientUnits="userSpaceOnUse"><stop class="i1ro3snza"/><stop offset=".824" class="knng2sb5f"/></linearGradient><linearGradient id="irsebVc" x1="12.002" x2="12.213" y1="7.797" y2="7.391" gradientUnits="userSpaceOnUse"><stop class="muhp3gb-x"/><stop offset="1" class="pteqlcbvj"/></linearGradient><linearGradient id="iYS2gKr" x1="11.534" x2="10.566" y1="5.184" y2="5.184" gradientUnits="userSpaceOnUse"><stop class="wqxrteb3u"/><stop offset="1" class="pmqh-db2s"/></linearGradient><linearGradient id="i33vZKb" x1="14.061" x2="13.092" y1="5.184" y2="5.184" gradientUnits="userSpaceOnUse"><stop class="wqxrteb3u"/><stop offset="1" class="pmqh-db2s"/></linearGradient><linearGradient id="iexauib" x1="13.721" x2="13.575" y1="5.861" y2="5.951" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i3N10Zd" x1="11.67" x2="11.524" y1="5.861" y2="5.951" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iaPypic" x1="15.412" x2="14.05" y1="2.932" y2="5.276" gradientUnits="userSpaceOnUse"><stop class="y_ccjxb5k"/><stop offset="1" class="w39yz6l0u"/></linearGradient><linearGradient id="iJGx8Rc" x1="15.339" x2="13.856" y1="3.43" y2="4.383" gradientUnits="userSpaceOnUse"><stop class="wzt3udgik"/><stop offset="1" class="gn591vgmd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-dancing-medium-dark" /></template>
<style>
.a-zqzeldx {
  d: path("M6.386 12.84c1.43 1.244 3.316.958 4.08.691v-3.65h5.71c.407-1.046.122-1.935-.187-2.42a.22.22 0 0 1-.023-.19c.065-.185.152-.485.163-.722c.025-.52-.136-.558-.15-1.273c-.016-.715-.243-.979-.617-1.59c-.303-.493-1.082-.814-1.557-1.002c-.521-.207-.706-.598-1.492-.598c-.607 0-1.007.308-1.283.575a.67.67 0 0 1-.378.182c-.966.129-1.789.58-2.244 1.422c-.267.494-.291 1.27-.288 1.8a.42.42 0 0 1-.332.406c-1.206.272-2.09.97-2.51 1.761c-.455.863-.68 3.055 1.108 4.609");
}

.a0kmoyxfg {
  stop-color: var(--svg-color--795354, #795354);
}

.a1xx86brr {
  stop-color: var(--svg-color--745447, #745447);
  stop-opacity: 0;
}

.a2ysf6bzt {
  d: path("m8.196 27.901l-.004.008a1.6 1.6 0 0 0-.18.883c.043.36.309.727.784 1.04c.257.17.594.062.751-.201l1.034-1.73z");
}

.a9-b904md {
  fill: var(--svg-color--9c756d, #9C756D);
  d: path("m19.653 28.71l-2.687-5.53l1.851-1.57l3.541 8.133a.1.1 0 0 1-.092.14h-.769c-1.012 0-1.594-.586-1.844-1.172");
}

.bds0mc2jk {
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.bgcikgb_z {
  d: path("M14.593 6.616a.5.5 0 1 0 0-1.002a.5.5 0 0 0 0 1.002");
}

.bw1rz3b-f {
  stop-color: var(--svg-color--443339, #443339);
  stop-opacity: 0;
}

.bx8w24b7x {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M12.875 5.85c.123-.218.312-.39.716-.39c.178 0 .349.05.5.172c.126.101.11.23.012.28l-.26.147c-.303-.098-.64-.111-.969-.21");
}

.bzjd0s3dz {
  stop-color: var(--svg-color--ff4660, #FF4660);
  stop-opacity: 0;
}

.c4hclxboa {
  stop-color: var(--svg-color--e73e59, #E73E59);
}

.cgagdkbfp {
  stop-color: var(--svg-color--6d4f42, #6D4F42);
}

.chm_zob8h {
  stop-color: var(--svg-color--7a5449, #7A5449);
}

.chywufrfu {
  stop-color: var(--svg-color--784554, #784554);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cn11jacls {
  stop-color: var(--svg-color--906d67, #906D67);
}

.cpmw12bkg {
  stop-color: var(--svg-color--cc2e32, #CC2E32);
}

.cz3brismi {
  stop-color: var(--svg-color--926d61, #926D61);
}

.d_b_m49gm {
  stop-color: var(--svg-color--94756c, #94756C);
}

.d1nygi1_s {
  stop-color: var(--svg-color--ff4660, #FF4660);
}

.d49vq-b3b {
  d: path("M26.74 13.508q-.222 0-.424.062c-.318.077-.621.221-.994.399h-.001c-.292.139-.626.298-1.043.46c-1.5.587-3.218.587-4.062.587H11.59c-1.933 0-3.534 1.566-3.559 3.499c-.007.536-.011 1.23-.011 1.79c0 1.797-1.662 3.73-2.672 4.687c-.7.664-.868 1.063-.967 1.297l-.014.034l-.02.044l.011.008a2.617 2.617 0 0 0 2.45 3.539h.965c-.499-.101-1.097-.246-1.566-.422c-1.04-.39-1.14-1.27-1.113-1.613c.02-.265.226-1.332 1.636-1.332c.95 0 2.031.064 3.022.123c.632.037 1.227.073 1.728.088c1.048.032 2.12-.065 2.57-1.215c.47-1.43.848-1.91 1.907-1.91c.493.03.872.049 1.124.062l.306.016c.7.047 1.452-.089 1.64-1.36c.211-1.421 1.067-1.552 1.672-1.53c.664.023 1.594.023 2.016-.29c.422-.312.468-.883.468-1.304s.147-1.164 1.172-1.266c1.149-.115 1.375-.36 1.532-.578c.226-.317.239-.694.187-1.266c-.07-.777.115-1.26.582-1.558c.617-.395 1.073.047 1.168.84c.023.19.052.446.085.736c.09.803.21 1.862.306 2.467v-3.618c0-.786-.615-1.43-1.39-1.474v-.002z");
}

.d7eg-abyg {
  fill: var(--svg-color--7e584e, #7E584E);
  d: path("m12.164 5.947l-.248.792c-.05.163.07.327.243.327h.366a.252.252 0 0 0 .243-.327l-.248-.792c-.053-.176-.3-.176-.356 0");
}

.dbrr_ge-k {
  stop-color: var(--svg-color--473a3e, #473A3E);
}

.dgweptk-f {
  stop-color: var(--svg-color--3d2c2f, #3D2C2F);
}

.dvmh07mfm {
  d: path("m12.164 5.947l-.248.792c-.05.163.07.327.243.327h.366a.252.252 0 0 0 .243-.327l-.248-.792c-.053-.176-.3-.176-.356 0");
}

.dz8dqqbnh {
  stop-color: var(--svg-color--d62645, #D62645);
}

.e_534j-zv {
  cx: 11.197px;
  cy: 5.792px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.181px;
  ry: 0.092px;
}

.e-084nbmr {
  stop-color: var(--svg-color--624543, #624543);
}

.e648o_baz {
  d: path("M9.95 14.54v1.67l5.735-.155c-.375-1.555-.368-3.258-.211-3.64c.156-.384.453-.774.476-1.29c.024-.516-.172-1-.476-1.484a3.5 3.5 0 0 1-.344-.805a.55.55 0 0 0-.513-.399h-.768c-.068 0-.109.09-.169.122l-.956.496l-1.204-.617c-.906.039-2.078.257-2.304.562c-.227.305-.25 1.008-.094 1.883s.43 1.812.648 2.36c.175.437.193 1.046.18 1.296");
}

.e7x_umu1z {
  d: path("M14.593 6.866a.75.75 0 1 0 0-1.501a.75.75 0 0 0 0 1.5");
}

.ebrwadt3p {
  stop-color: var(--svg-color--562d26, #562D26);
  stop-opacity: 0;
}

.ed0bwz-2w {
  stop-color: var(--svg-color--921c39, #921C39);
}

.emq3pu1ym {
  stop-color: var(--svg-color--da2e3d, #DA2E3D);
}

.en9rkbb0o {
  stop-color: var(--svg-color--6c1118, #6C1118);
  stop-opacity: 0;
}

.er3a68ttw {
  stop-color: var(--svg-color--774654, #774654);
  stop-opacity: 0;
}

.etzb8g0rx {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
}

.f-1fthf3z {
  d: path("M10.157 6.866a.75.75 0 1 0 0-1.501a.75.75 0 0 0 0 1.5");
}

.f4zah8e_v {
  d: path("M10.166 6.616a.5.5 0 1 0 0-1.002a.5.5 0 0 0 0 1.002");
}

.f88wzbb7k {
  stop-color: var(--svg-color--242223, #242223);
}

.fcfe9dfwi {
  stop-color: var(--svg-color--654342, #654342);
}

.ffknxknmx {
  stop-color: var(--svg-color--6f423c, #6F423C);
  stop-opacity: 0;
}

.fkpcsjb3b {
  fill: var(--svg-color--7b4f4b, #7B4F4B);
  d: path("M18.847 8.508h-4.116l.555 2.203h3.508c1.486 0 2.375-1.063 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.155.784-.215a1 1 0 0 0 .508-.343l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.167-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.133.12-.417.448-.492.804a2.8 2.8 0 0 0-.028.758c.013.151.024.303.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.ft5dv1b6b {
  fill: none;
}

.futtttqqr {
  fill: var(--svg-color--7e5a4d, #7E5A4D);
  d: path("M10.83 9.487c.288.55.075 1.23-.476 1.518l-3.072 1.57c-.257.133-.449.238-.543.613l-.332 1.27a1 1 0 0 0-.032.276l.04 1.756a.486.486 0 1 1-.973 0v-.807l-.568.408a.25.25 0 0 0-.103.218l.056.956a.486.486 0 1 1-.971.057l-.07-1.2c-.007-.126 0-.349.137-.528l.541-.869l.184-1.733a3.13 3.13 0 0 1 1.657-2.41l3.007-1.571a1.125 1.125 0 0 1 1.518.476");
}

.ga74agm1p {
  fill-rule: evenodd;
  d: path("m14.718 4.488l-.004.015c-.072.222-.282.352-.47.292c-.187-.061-.28-.29-.209-.512l.008-.02h-.039c-.226 0-.409-.159-.409-.356s.183-.356.409-.356h.007L14 3.506c-.043-.221.088-.433.293-.473c.194-.037.385.094.44.296l.004-.002c.181-.134.423-.113.54.045c.116.159.064.396-.118.53l-.016.01q.03.023.056.05c.162.168.178.415.036.551c-.133.128-.356.114-.517-.025");
}

.galfynzfj {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.457 5.487c.305 0 .562.21.632.494a.128.128 0 0 1-.125.159h-1.04a.107.107 0 0 1-.106-.127a.65.65 0 0 1 .64-.526");
}

.gc5jyu-5m {
  d: path("M9.97 5.527h.006l-.005-.124l-.005-.143c.01-.442.268-.614.378-.67l.024-.01l.024-.01a1.07 1.07 0 0 0 .554-.576l.039-.09a.123.123 0 0 1 .215-.024c.335.49.894.78 1.487.78h1.502c.084 0 .504.041.53.622l-.056 1.433c-.058 1.307-1.078 2.184-2.324 2.184s-2.266-.877-2.324-2.184z");
}

.gn591vgmd {
  stop-color: var(--svg-color--c32e4e, #C32E4E);
}

.gojf2jtsr {
  d: path("M13.329 5.703c.03.039-.032.087-.103.14c-.07.052-.122.089-.151.05c-.03-.04.003-.114.073-.167c.07-.052.151-.063.18-.023");
}

.gq7r-y_jo {
  d: path("M11.702 5.98c0-.134-.108-.223-.138-.25l-.134.13l.083.167z");
}

.gr1si2b-x {
  stop-color: var(--svg-color--7b5958, #7B5958);
}

.h1j4vebkc {
  stop-color: var(--svg-color--921c39, #921C39);
  stop-opacity: 0;
}

.h84ffkb2i {
  stop-color: var(--svg-color--d42f4e, #D42F4E);
}

.h9hedgb-i {
  stop-color: var(--svg-color--5d3a3f, #5D3A3F);
}

.hv09-7aho {
  stop-color: var(--svg-color--d62645, #D62645);
  stop-opacity: 0;
}

.i_adio88s {
  d: path("M13.36 5.614a.416.416 0 0 1 .402.526h-.804a.418.418 0 0 1 .403-.526");
}

.i-td5rxsk {
  stop-color: var(--svg-color--851e29, #851E29);
  stop-opacity: 0;
}

.i1ro3snza {
  stop-color: var(--svg-color--835b53, #835B53);
}

.idx3obcoi {
  fill: var(--svg-color--000, #000);
  d: path("M13.122 6.03c0-.132.106-.238.238-.238a.237.237 0 0 1 .212.348h-.422a.2.2 0 0 1-.028-.11");
}

.ifk4wkbgx {
  d: path("m8.192 27.91l.719-1.45l2.555-.038l-1.919 3.209c-.157.263-.494.371-.751.202c-.475-.313-.741-.682-.784-1.04a1.6 1.6 0 0 1 .18-.884");
}

.ivwd4jbev {
  stop-color: var(--svg-color--7b4e4b, #7B4E4B);
  stop-opacity: 0;
}

.jcz4yrb9y {
  stop-color: var(--svg-color--916f68, #916F68);
  stop-opacity: 0;
}

.jk372--tq {
  stop-color: var(--svg-color--794f52, #794F52);
}

.k2sx12b0p {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
}

.ket8l8b0j {
  stop-color: var(--svg-color--d32659, #D32659);
}

.kkds9sbif {
  fill-rule: evenodd;
  d: path("M14.85 4.965c.013-.04.067-.057.1-.032a.599.599 0 1 0 .711-.963a.067.067 0 0 1 0-.104a.598.598 0 0 0-.705-.967c-.035.025-.09.007-.102-.034a.6.6 0 1 0-1.14.368c.014.04-.02.087-.062.087h-.004a.599.599 0 0 0 0 1.197c.04 0 .073.044.061.083a.599.599 0 0 0 1.14.365");
}

.kn22s4txk {
  stop-color: var(--svg-color--755252, #755252);
}

.knng2sb5f {
  stop-color: var(--svg-color--835b53, #835B53);
  stop-opacity: 0;
}

.kv4_lccbf {
  stop-color: var(--svg-color--8c726a, #8C726A);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lqgx_abdw {
  stop-color: var(--svg-color--612f33, #612F33);
}

.lze6x5b3f {
  stop-color: var(--svg-color--d32659, #D32659);
  stop-opacity: 0;
}

.m472w0fxa {
  d: path("m10.757 5.286l-.002.001a.125.125 0 0 1-.128-.214l.002-.002l.004-.002l.015-.009l.054-.027a2 2 0 0 1 .192-.075c.158-.051.38-.094.62-.051a.125.125 0 0 1-.044.246c-.186-.033-.365 0-.5.043a1.3 1.3 0 0 0-.203.084z");
}

.m4wre3b4e {
  stop-color: var(--svg-color--73544f, #73544F);
  stop-opacity: 0;
}

.m8u-j2bfh {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
}

.mgek_kbvl {
  fill: var(--svg-color--774555, #774555);
  d: path("m12.159 6.011l-.319.793a.252.252 0 0 0 .243.326h.367a.252.252 0 0 0 .243-.326l-.248-.793c-.053-.175-.23-.175-.286 0");
}

.mkrjvhq2k {
  stop-color: var(--svg-color--906d67, #906D67);
  stop-opacity: 0;
}

.mudzph12f {
  d: path("M13.73 5.975a.4.4 0 0 0-.107-.215l-.121.132l.054.106z");
}

.muhp3gb-x {
  stop-color: var(--svg-color--7f595b, #7F595B);
}

.mz51gmfzq {
  stop-color: var(--svg-color--e73e59, #E73E59);
  stop-opacity: 0;
}

.nhe36etun {
  stop-color: var(--svg-color--3d2c2f, #3D2C2F);
  stop-opacity: 0;
}

.njr-tqk5i {
  d: path("M11.324 5.614a.416.416 0 0 0-.401.526h.804a.42.42 0 0 0-.403-.526");
}

.nwegx7xkg {
  stop-color: var(--svg-color--99756c, #99756C);
}

.o1_zjo1ay {
  d: path("M10.929 4.013c-.174.445-.931.811-1.27.9c-.113-.903.237-1.992 1.342-1.795l.187.722c-.187-.053-.226.087-.259.173");
}

.o5cnyqbgj {
  d: path("M18.847 8.508h-4.116l.555 2.203h3.508c1.486 0 2.375-1.063 2.297-2.656l-.076-2.34a.1.1 0 0 1 .077-.102c.205-.053.56-.155.784-.215a1 1 0 0 0 .508-.343l.506-.744a.546.546 0 1 0-.907-.609l-.294.443a.17.17 0 0 1-.074.063c-.395.167-.904.173-1.137.163l.28-.268a.533.533 0 0 0-.705-.798l-.4.328c-.133.12-.417.448-.492.804a2.8 2.8 0 0 0-.028.758c.013.151.024.303.015.455l-.15 2.716a.15.15 0 0 1-.15.142");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ouau4qbku {
  stop-color: var(--svg-color--6e3b49, #6E3B49);
}

.p_c4y8b-n {
  stroke: var(--svg-color--362c2f, #362C2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M13.247 5.009c.15-.037.524-.019.774.16");
}

.p224_4b9x {
  stop-color: var(--svg-color--3f2b31, #3F2B31);
}

.p7beq2bgt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M13.329 5.703c.03.039-.032.087-.103.14c-.07.052-.122.089-.151.05c-.03-.04.003-.114.073-.167c.07-.052.151-.063.18-.023");
}

.pfi2macjv {
  fill: var(--svg-color--000, #000);
  d: path("M11.562 6.03a.237.237 0 0 0-.239-.238a.237.237 0 0 0-.212.348h.422a.24.24 0 0 0 .029-.11");
}

.pjtqv3e9z {
  stop-color: var(--svg-color--936b63, #936B63);
}

.pk_7ilbgy {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.342 7.473c-.243 0-.471-.059-.663-.16c-.066-.035-.136.04-.095.101a.9.9 0 0 0 1.516 0c.04-.063-.03-.136-.095-.102a1.4 1.4 0 0 1-.663.16Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pmqh-db2s {
  stop-color: var(--svg-color--2c1829, #2C1829);
}

.ppa6_abwh {
  stop-color: var(--svg-color--9a3037, #9A3037);
}

.pteqlcbvj {
  stop-color: var(--svg-color--7f595b, #7F595B);
  stop-opacity: 0;
}

.q_d1lub6r {
  stop-color: var(--svg-color--f22b4e, #F22B4E);
  stop-opacity: 0;
}

.q6mg8ibon {
  stop-color: var(--svg-color--73544f, #73544F);
}

.r38-lhbhs {
  stop-color: var(--svg-color--e9283f, #E9283F);
}

.r7_ojkbmv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.227 5.487a.65.65 0 0 0-.632.494a.128.128 0 0 0 .125.159h1.04c.067 0 .12-.06.106-.127a.65.65 0 0 0-.64-.526");
}

.raocb-buh {
  stop-color: var(--svg-color--916f68, #916F68);
}

.rhhoifucn {
  cx: 11.197px;
  cy: 5.792px;
  rx: 0.181px;
  ry: 0.092px;
}

.rlatyn0wa {
  stop-color: var(--svg-color--45383c, #45383C);
  stop-opacity: 0;
}

.rttxvnbop {
  d: path("M12.06 2.467c-.527-.117-1.233.462-1.288.658c.72 1.688 1.69 1.579 3.032 1.528c.745-.028.805.237.867.399c.124-2.122-1.406-2.32-2.61-2.585");
}

.rxdm1gb4b {
  stop-color: var(--svg-color--6c1118, #6C1118);
}

.s0bi7iy1o {
  stop-color: var(--svg-color--7b5958, #7B5958);
  stop-opacity: 0;
}

.s3-919bdo {
  stop-color: var(--svg-color--774658, #774658);
  stop-opacity: 0;
}

.sh2s77xqm {
  stop-color: var(--svg-color--663c4d, #663C4D);
}

.t-07fdchd {
  stop-color: var(--svg-color--896053, #896053);
}

.ta7v5vpcw {
  stop-color: var(--svg-color--7c4f55, #7C4F55);
  stop-opacity: 0;
}

.tk4_g-b3s {
  stop-color: var(--svg-color--94756c, #94756C);
  stop-opacity: 0;
}

.u6ezkbbkd {
  stop-color: var(--svg-color--ee3148, #EE3148);
}

.u7harwjoq {
  stop-color: var(--svg-color--784554, #784554);
  stop-opacity: 0;
}

.u8l8bnbbx {
  fill: var(--svg-color--ff444f, #FF444F);
  d: path("m19.082 27.535l.571 1.176c.25.586.832 1.172 1.844 1.172h.77a.1.1 0 0 0 .091-.14l-.628-1.444z");
}

.umf8cbcnm {
  stop-color: var(--svg-color--2e1a26, #2E1A26);
}

.uwqjkbvol {
  d: path("M15.782 29.914h-8.58c-.823-.182-2.47-.85-2.47-2.06c0-1.514 1.345-2.514 1.25-2.576c-.074-.05 3.025-2.425 4.583-3.606l13.045-5.58c.87-.697 2.796-2.081 3.535-2.037c.738.043 1.021 1.007 1.07 1.483v5.533c0 .921-.304 1.951-.985 2.404c-.68.453-1.212.343-2.26.343c-1.173 0-1.454.336-1.908 1.749c-.363 1.13-.985 1.381-1.9 1.381h-1.189c-.805 0-1.345.172-1.798 1.67c-.4 1.08-1.408 1.296-2.393 1.296");
}

.v00lg4c1x {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M12.342 7.473c-.243 0-.471-.059-.663-.16c-.066-.035-.136.04-.095.101a.9.9 0 0 0 1.516 0c.04-.063-.03-.136-.095-.102a1.4 1.4 0 0 1-.663.16");
}

.v2w0c2b8h {
  stop-color: var(--svg-color--6f423c, #6F423C);
}

.v9xkymirg {
  fill: var(--svg-color--734952, #734952);
  d: path("m5.042 17.508l-.35-.457l-.578-1.078l1.38-.516l.046 1.254l.2.26a.44.44 0 1 1-.698.537");
}

.vwva7zb6f {
  fill-rule: evenodd;
  d: path("m14.082 5.073l-.064.107za.125.125 0 0 1-.128.214l-.002-.001l-.01-.006l-.043-.021a1 1 0 0 0-.16-.063a1.06 1.06 0 0 0-.5-.043a.125.125 0 1 1-.043-.246c.24-.043.46 0 .62.05a1.5 1.5 0 0 1 .26.112l.004.002z");
}

.w_bi9zfnz {
  stop-color: var(--svg-color--724c46, #724C46);
}

.w39yz6l0u {
  stop-color: var(--svg-color--dc2d68, #DC2D68);
}

.w4rlmo2dn {
  stop-color: var(--svg-color--242223, #242223);
  stop-opacity: 0;
}

.whopo0y2h {
  stop-color: var(--svg-color--200e23, #200E23);
}

.wqxrteb3u {
  stop-color: var(--svg-color--2a1d27, #2A1D27);
}

.ws5-tkbbq {
  d: path("m13.116 10.256l-1.752-1.6l.383-.172h2.04V9.96a.4.4 0 0 1-.67.296");
}

.wzt3udgik {
  stop-color: var(--svg-color--c9334f, #C9334F);
}

.x_atgxb_v {
  stop-color: var(--svg-color--911c39, #911C39);
}

.x_nmsobjl {
  stop-color: var(--svg-color--45383c, #45383C);
}

.xbj9zzvwg {
  stop-color: var(--svg-color--b01b4b, #B01B4B);
  stop-opacity: 0;
}

.xz2vy3rji {
  stop-color: var(--svg-color--443339, #443339);
}

.y_ccjxb5k {
  stop-color: var(--svg-color--e73950, #E73950);
}

.y4inpcddo {
  stop-color: var(--svg-color--734945, #734945);
}

.y6gj-0bkn {
  stop-color: var(--svg-color--4b2526, #4B2526);
}

.y95rwebpc {
  stroke: var(--svg-color--362c2f, #362C2F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M11.479 5.009c-.15-.037-.525-.019-.775.16");
}

.y9u9iibtz {
  stop-color: var(--svg-color--562d26, #562D26);
}

.yhc7rmbsi {
  stop-color: var(--svg-color--7f4e5c, #7F4E5C);
}

.yu3j8mbni {
  stop-color: var(--svg-color--db2f4a, #DB2F4A);
  stop-opacity: 0;
}

.yung1xdgy {
  stop-color: var(--svg-color--851e29, #851E29);
}

.zdnvr8b2y {
  fill: var(--svg-color--635d5f, #635D5F);
  d: path("M11.81 5.85c-.124-.218-.312-.39-.717-.39a.77.77 0 0 0-.5.172c-.126.101-.11.23-.012.28l.26.147c.303-.098.64-.111.969-.21");
}

.zrq_ottju {
  stop-color: var(--svg-color--693945, #693945);
}

.zstr-2b3h {
  stop-color: var(--svg-color--ff3b57, #FF3B57);
}

</style>

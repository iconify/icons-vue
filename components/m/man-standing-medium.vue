<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y_mkc7b6b"/><path class="izcj2zmqt"/><g filter="url(#ipJPyPc)"><path class="a03v9qbdr"/><path fill="url(#irrGo3d)" class="m8gz-0b5a"/></g><path class="t9px69bkt"/><path fill="url(#iMZomde)" class="dxtmqmqaf"/><path fill="url(#iSKF8SL)" class="dxtmqmqaf"/><path class="g7lbglbgf"/><path fill="url(#iexrOud)" class="et-r-fdsf"/><path fill="url(#iGbdahb)" class="et-r-fdsf"/><path fill="url(#iQ2UD0b)" class="et-r-fdsf"/><path fill="url(#ixqcsxe)" class="et-r-fdsf"/><g filter="url(#iKdBVzQ)"><path class="ofbrbub6c"/></g><path class="gek68lb2e"/><path fill="url(#i0hpiHb)" class="oi8jickna"/><path fill="url(#iLYaexd)" class="oi8jickna"/><g filter="url(#iWYKzUc)"><path class="dmwfkac9c"/></g><path fill="url(#iyqy0Lc)" class="p07i09slr"/><path fill="url(#i5PPVDd)" class="p07i09slr"/><path fill="url(#ixAgKIb)" class="p07i09slr"/><path fill="url(#iHq8zOc)" class="p07i09slr"/><g filter="url(#iHwWDgc)"><path fill="url(#invnxNI)" class="e1d2xybku"/><path fill="url(#ipDNFDc)" class="e1d2xybku"/></g><path fill="url(#inj02Oe)" class="e1d2xybku"/><path fill="url(#iPGtjwd)" class="e1d2xybku"/><path fill="url(#iKn0qge)" class="e1d2xybku"/><path fill="url(#i6F7lxS)" class="qlcrdsbcc"/><g filter="url(#iWRUhAd)"><path class="wa3nobd_c"/></g><path fill="url(#iTLDONe)" class="x92fm7bvu"/><path fill="url(#iXRqjfc)" class="x92fm7bvu"/><g filter="url(#iiuswLd)"><path class="de6owvbbq"/></g><g filter="url(#iu2om7l)"><circle fill="url(#ikLYy6d)" class="wma78obnb"/></g><circle fill="url(#ibHDqCd)" class="wma78obnb"/><g filter="url(#i9HgQve)"><circle fill="url(#iWUoFdb)" class="chc9c-1uv"/></g><g filter="url(#i9ksK8o)"><circle fill="url(#iaeAj5b)" class="dtztswbcc"/><circle fill="url(#iCSNQJe)" class="dtztswbcc"/></g><g filter="url(#iB7jfTd)"><circle class="m6qbpgbhr"/><circle fill="url(#i0yac7t)" class="imz-u4bms"/><circle fill="url(#iWwy9iF)" class="imz-u4bms"/></g><g filter="url(#iq0zfId)"><path fill="url(#iNVc3lc)" class="w_7sj9bks"/><path fill="url(#i0fGPpc)" class="w_7sj9bks"/><path fill="url(#iDNaqrb)" class="w_7sj9bks"/></g><path fill="url(#iTQS40d)" class="mj9v0bbqu"/><path fill="url(#iAE9aBc)" class="mj9v0bbqu"/><path fill="url(#iuQn5he)" class="mj9v0bbqu"/><g filter="url(#iPevVDE)"><path fill="url(#iXlHK3d)" class="ozpey3bvw"/></g><g filter="url(#i6pwpqb)"><path class="bseq01blv"/><path fill="url(#icN17eb)" class="i5n762bmp"/><path fill="url(#imMYISd)" class="i5n762bmp"/><path fill="url(#iEVx4UF)" class="i5n762bmp"/><path fill="url(#iVKlnac)" class="i5n762bmp"/></g><g filter="url(#iSLTmod)"><path class="qzjv9wb_n"/></g><g filter="url(#ioAYNSc)"><path class="aapmlhbob"/><path fill="url(#iG9u1bd)" class="d1jb8ccpv"/><path fill="url(#ispzjmL)" class="d1jb8ccpv"/><path fill="url(#ikA2DMe)" class="d1jb8ccpv"/><path fill="url(#ikuofMc)" class="d1jb8ccpv"/></g><path stroke="url(#i96vgkb)" class="ero-lfszg"/><g filter="url(#iCCjM4c)"><path class="ob07l54eq"/><path fill="url(#iov4sAc)" class="wxdu2lj0o"/></g><g filter="url(#i0Mezlb)"><path class="u5jeodkbz"/><path fill="url(#iwHY88d)" class="ywr6uvbgg"/></g><path class="u0xg32bgc"/><path fill="url(#i2hhlQd)" class="i-9s0ybju"/><path class="hj6fgb6dy"/><g filter="url(#isKoyrc)"><path class="gu19b_bxx"/><path fill="url(#izgC2He)" class="agon8lbfr"/></g><g filter="url(#ib9WRqd)"><path fill="url(#iuq4hjd)" class="d-8iesb9b"/></g><path class="ob3p6mbly"/><path fill="url(#iACwkTJ)" class="hv6ftmbbs"/><path class="wpolc4b9j"/><g filter="url(#iZGAaCc)"><path fill="url(#iG7IPgp)" class="qxmupoqkj"/></g><g filter="url(#i1MwMub)"><ellipse transform="rotate(-27.914 14.89 5.456)" class="nlrjo9pll"/><ellipse fill="url(#i6Blknb)" transform="rotate(-27.914 14.89 5.456)" class="qi8gzubuf"/></g><g filter="url(#ifrcmrb)"><path stroke="url(#irq5aPd)" class="kdvk3hv7t"/></g><g filter="url(#i9R1Ikb)"><path stroke="url(#i73NS9c)" class="aatfg3dvl"/></g><g filter="url(#iyd7Qce)"><path stroke="url(#iDAUbzd)" class="m9k7mpbqe"/></g><defs><radialGradient id="irrGo3d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84375 0 0 -12.369 13.357 16.715)" gradientUnits="userSpaceOnUse"><stop offset=".138" class="zay0pib-e"/><stop offset="1" class="f283vybwl"/></radialGradient><radialGradient id="iMZomde" cx="0" cy="0" r="1" gradientTransform="matrix(1.60938 0 0 15.4135 18.872 16.715)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="nrk1uwb9l"/><stop offset="1" class="jewrngbdz"/></radialGradient><radialGradient id="iSKF8SL" cx="0" cy="0" r="1" gradientTransform="matrix(.1836 -.5625 .3991 .13026 19.319 19.109)" gradientUnits="userSpaceOnUse"><stop class="w48qw8bka"/><stop offset="1" class="q7l1h8mqg"/></radialGradient><radialGradient id="iexrOud" cx="0" cy="0" r="1" gradientTransform="rotate(-168.523 7.537 5.838)scale(2.27735 4.86372)" gradientUnits="userSpaceOnUse"><stop offset=".638" class="rsfoz3blw"/><stop offset="1" class="nwf629gla"/></radialGradient><radialGradient id="iGbdahb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.51587 1.2383 -.95063 -1.16372 14.562 8.915)" gradientUnits="userSpaceOnUse"><stop class="pm40e6_le"/><stop offset="1" class="asa-ks78a"/></radialGradient><radialGradient id="ixqcsxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.35938 2.17188 -.8973 -.14848 13.246 11.794)" gradientUnits="userSpaceOnUse"><stop class="d5ei9kbfm"/><stop offset="1" class="a7wdambul"/></radialGradient><radialGradient id="i0hpiHb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -.3125 1.2963 3.62963 18.794 12.06)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="to0orccvb"/><stop offset="1" class="tb5vgbckn"/></radialGradient><radialGradient id="i5PPVDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.35938 1.91919 0 16 18.185)" gradientUnits="userSpaceOnUse"><stop class="kcjik5o6k"/><stop offset="1" class="j6ndfp4vo"/></radialGradient><radialGradient id="ixAgKIb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.26953 1.85938 0 18.075 28.548)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="iHq8zOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.32813 1.20581 0 14.794 28.638)" gradientUnits="userSpaceOnUse"><stop class="x7tdxqavt"/><stop offset="1" class="cssy6ccya"/></radialGradient><radialGradient id="ipDNFDc" cx="0" cy="0" r="1" gradientTransform="rotate(140.013 7.411 8.269)scale(2.52874 3.92481)" gradientUnits="userSpaceOnUse"><stop class="u_3hhfbdm"/><stop offset="1" class="wz3lzhbxc"/></radialGradient><radialGradient id="iKn0qge" cx="0" cy="0" r="1" gradientTransform="matrix(.23437 1.1172 -3.2104 .6735 15.278 8.552)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="p56j8ub-b"/><stop offset="1" class="lw7z9gbtl"/></radialGradient><radialGradient id="i6F7lxS" cx="0" cy="0" r="1" gradientTransform="matrix(1.42712 .66406 -.8419 1.8093 15.444 8.956)" gradientUnits="userSpaceOnUse"><stop offset=".526" class="ha_-8_b3a"/><stop offset="1" class="jm3khdb3g"/></radialGradient><radialGradient id="iXRqjfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66284 -.84375 .32903 -.64844 19.566 29.498)" gradientUnits="userSpaceOnUse"><stop class="z3z2fqbpi"/><stop offset="1" class="qnuhplbln"/></radialGradient><radialGradient id="ikLYy6d" cx="0" cy="0" r="1" gradientTransform="matrix(.80803 0 0 1.41405 13.067 5.815)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="ibHDqCd" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 8.632 -.311)scale(.76285)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="iCSNQJe" cx="0" cy="0" r="1" gradientTransform="matrix(.38066 -.27718 .31636 .43447 18.387 5.693)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="i0yac7t" cx="0" cy="0" r="1" gradientTransform="matrix(.37815 -.69552 .4071 .22133 18.197 6.193)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="iWwy9iF" cx="0" cy="0" r="1" gradientTransform="rotate(44.709 2.039 25.055)scale(.16799 .21656)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="i0fGPpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60184 .74073 0 17.102 5.23)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="iDNaqrb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6327 .78683 0 15.003 5.29)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iuQn5he" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.83483 -4.75303 0 15.963 5.109)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="dcym8repk"/><stop offset="1" class="fkee40m0y"/></radialGradient><radialGradient id="icN17eb" cx="0" cy="0" r="1" gradientTransform="matrix(.36736 -1.36138 .50484 .13623 18.022 3.924)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="imMYISd" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -25.272 189.577)scale(1.76859 .95096)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iEVx4UF" cx="0" cy="0" r="1" gradientTransform="matrix(0 .77318 -1.19743 0 16.022 1.854)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="iVKlnac" cx="0" cy="0" r="1" gradientTransform="matrix(1.4154 -1.03724 1.62502 2.21746 13.053 4.993)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="ikuofMc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .09066 -.29128 0 16.172 6.554)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iov4sAc" cx="0" cy="0" r="1" gradientTransform="matrix(.04798 -.27778 .82176 .14193 17.146 4.855)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iwHY88d" cx="0" cy="0" r="1" gradientTransform="matrix(.04798 -.27777 .82182 .14195 14.776 4.855)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="i2hhlQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .37349 -.59407 0 17.025 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="izgC2He" cx="0" cy="0" r="1" gradientTransform="rotate(-127.813 9.816 -1.374)scale(.17414 .23975)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iACwkTJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3735 -.5941 0 15.016 5.5)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i6Blknb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00356 -.22745 .2734 -.00428 14.885 5.602)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="ipJPyPc" width="2.311" height="8.028" x="11.403" y="12.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.666667 0 0 0 0 0.505882 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iKdBVzQ" width="1.464" height="6.913" x="19.164" y="12.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".25"/></filter><filter id="iWYKzUc" width="6.169" height="12.453" x="13.016" y="16.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.462745 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iHwWDgc" width="6.517" height="7.994" x="12.941" y="8.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.368627 0 0 0 0 0.560784 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iWRUhAd" width="3.316" height="1.848" x="12.434" y="28.548" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.235294 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iiuswLd" width="6.594" height="13.766" x="12.841" y="15.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".5"/></filter><filter id="iu2om7l" width="1.737" height="1.537" x="13.067" y="5.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="i9HgQve" width="1.916" height="1.916" x="12.877" y="4.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".25"/></filter><filter id="i9ksK8o" width="1.787" height="1.787" x="17.447" y="4.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iB7jfTd" width="1.916" height="1.916" x="17.258" y="4.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".25"/></filter><filter id="iq0zfId" width="4.777" height="5.638" x="13.646" y="3.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iPevVDE" width="2.955" height="2.412" x="15.6" y="2.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".25"/></filter><filter id="i6pwpqb" width="5.802" height="3.904" x="13.12" y="1.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="iSLTmod" width="2.31" height="2.735" x="14.756" y="4.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".375"/></filter><filter id="ioAYNSc" width="1.064" height="1.435" x="15.49" y="5.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".05"/></filter><filter id="iCCjM4c" width="1.507" height="1.078" x="16.566" y="3.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="i0Mezlb" width="1.507" height="1.078" x="14.196" y="3.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_178"/></filter><filter id="isKoyrc" width=".47" height=".428" x="16.633" y="5.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".05"/></filter><filter id="ib9WRqd" width=".626" height=".636" x="16.965" y="5.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".1"/></filter><filter id="iZGAaCc" width=".67" height=".695" x="14.92" y="5.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".1"/></filter><filter id="i1MwMub" width=".528" height=".432" x="14.627" y="5.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".05"/></filter><filter id="ifrcmrb" width="1.202" height=".548" x="16.611" y="4.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".05"/></filter><filter id="i9R1Ikb" width="1.237" height=".575" x="14.208" y="4.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".05"/></filter><filter id="iyd7Qce" width=".869" height="1.45" x="13.441" y="3.224" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_178" stdDeviation=".125"/></filter><linearGradient id="iQ2UD0b" x1="12.466" x2="12.466" y1="12.865" y2="12.712" gradientUnits="userSpaceOnUse"><stop class="sc4il2d7k"/><stop offset="1" class="m85-u4b_v"/></linearGradient><linearGradient id="iLYaexd" x1="19.747" x2="19.747" y1="12.951" y2="12.247" gradientUnits="userSpaceOnUse"><stop class="bowp4_b2y"/><stop offset="1" class="kl0728zpw"/></linearGradient><linearGradient id="iyqy0Lc" x1="16" x2="16" y1="16.095" y2="16.529" gradientUnits="userSpaceOnUse"><stop class="sb3cb-bog"/><stop offset="1" class="hpe4_756h"/></linearGradient><linearGradient id="invnxNI" x1="16" x2="16" y1="9.185" y2="16.146" gradientUnits="userSpaceOnUse"><stop class="dp48kcpaa"/><stop offset="1" class="mwrvsh4-t"/></linearGradient><linearGradient id="inj02Oe" x1="17.606" x2="17.606" y1="16.146" y2="14.029" gradientUnits="userSpaceOnUse"><stop class="voaf13bac"/><stop offset="1" class="tpb8kfbdc"/></linearGradient><linearGradient id="iPGtjwd" x1="17.231" x2="17.231" y1="16.099" y2="15.81" gradientUnits="userSpaceOnUse"><stop class="nb4vlrbxr"/><stop offset="1" class="f7w9xyx3p"/></linearGradient><linearGradient id="iTLDONe" x1="18.247" x2="16.5" y1="29.81" y2="29.607" gradientUnits="userSpaceOnUse"><stop class="c2i7i45cq"/><stop offset="1" class="wwbz7ibcz"/></linearGradient><linearGradient id="iWUoFdb" x1="13.835" x2="13.54" y1="5.943" y2="5.943" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="iaeAj5b" x1="18.716" x2="18.339" y1="5.312" y2="6.48" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="iNVc3lc" x1="17.88" x2="14.364" y1="5.994" y2="6.518" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="iTQS40d" x1="13.537" x2="14.403" y1="7.235" y2="7.204" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iAE9aBc" x1="18.287" x2="17.775" y1="6.848" y2="6.803" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="iXlHK3d" x1="15.777" x2="19.527" y1="4.62" y2="3.277" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iG9u1bd" x1="15.624" x2="16.056" y1="6.297" y2="6.297" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="ispzjmL" x1="16.454" x2="15.982" y1="6.446" y2="6.439" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="ikA2DMe" x1="16.111" x2="16.111" y1="6.788" y2="6.524" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="i96vgkb" x1="15.544" x2="15.744" y1="7.531" y2="7.215" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iuq4hjd" x1="17.383" x2="17.238" y1="5.525" y2="5.614" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iG7IPgp" x1="15.358" x2="15.214" y1="5.525" y2="5.614" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="irq5aPd" x1="17.39" x2="17.197" y1="4.54" y2="4.145" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i73NS9c" x1="14.947" x2="14.4" y1="4.481" y2="4.252" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iDAUbzd" x1="13.875" x2="13.875" y1="3.554" y2="4.547" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-standing-medium" /></template>
<style>
.a03v9qbdr {
  fill: var(--svg-color--996a67, #996A67);
  d: path("M12.112 20.524c-.938-1.982-.769-6.258-.488-7.823h1.672c-.071 2.425.04 5.243.178 6.511c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.099a.176.176 0 0 0-.12.201c.061.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.a7wdambul {
  stop-color: var(--svg-color--257ad3, #257AD3);
  stop-opacity: 0;
}

.aapmlhbob {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.846 5.683l-.245.783c-.05.16.07.322.24.322h.362a.25.25 0 0 0 .24-.322l-.245-.783c-.053-.173-.297-.173-.352 0");
}

.aatfg3dvl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.383 4.734c.15-.133.48-.273.887-.208");
}

.agon8lbfr {
  d: path("M16.996 5.368c.029.039-.032.087-.102.139s-.121.088-.15.05c-.03-.04.003-.114.073-.166s.15-.062.179-.023");
}

.asa-ks78a {
  stop-color: var(--svg-color--3a87b0, #3A87B0);
  stop-opacity: 0;
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bowp4_b2y {
  stop-color: var(--svg-color--4e73c8, #4E73C8);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bseq01blv {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m18.24 2.832l.198.098c.346.172.543.565.47.982l-.272 1.4c-.025.145-.12.242-.264.246h-.008s.025-.418.05-.663c.02-.2-.015-.26-.198-.442a.58.58 0 0 1-.173-.393v-.393a.265.265 0 0 0-.198-.246c-.296-.073-.914-.196-1.803-.196s-1.506.123-1.803.196a.24.24 0 0 0-.197.246v.393a.49.49 0 0 1-.173.393l-.074.073c-.1.074-.149.221-.149.344c.025.27.05.663.05.663h-.023a.29.29 0 0 1-.273-.245l-.272-1.4a.94.94 0 0 1 .494-.958l.197-.098c.124-.074.247-.172.37-.27l.445-.467a.9.9 0 0 1 1.013-.147c.247.073.519.073.766 0a1.11 1.11 0 0 1 1.087.245l.37.369c.099.123.222.196.37.27");
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c2i7i45cq {
  stop-color: var(--svg-color--5a3f7c, #5A3F7C);
}

.chc9c-1uv {
  cx: 13.835px;
  cy: 5.815px;
  r: 0.458px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cssy6ccya {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d-8iesb9b {
  d: path("M17.392 5.638a.4.4 0 0 0-.107-.213l-.12.131l.055.105z");
}

.d1jb8ccpv {
  d: path("m15.846 5.683l-.245.783c-.05.16.07.322.24.322h.362a.25.25 0 0 0 .24-.322l-.245-.783c-.053-.173-.297-.173-.352 0");
}

.d5ei9kbfm {
  stop-color: var(--svg-color--257ad3, #257AD3);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dcym8repk {
  stop-color: var(--svg-color--9b7168, #9B7168);
  stop-opacity: 0;
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.de6owvbbq {
  fill: var(--svg-color--9d98a2, #9D98A2);
  d: path("m13.841 16.466l.469 11.766h.812v-10.61h2.203v10.61h.672l.438-11.766z");
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.dmwfkac9c {
  fill: var(--svg-color--827a8a, #827A8A);
  d: path("m13.016 16.095l.484 12.453h2l.238-9.523c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.dp48kcpaa {
  stop-color: var(--svg-color--46a3f0, #46A3F0);
}

.dtztswbcc {
  cx: 18.216px;
  cy: 5.815px;
  r: 0.769px;
}

.dxtmqmqaf {
  d: path("M19.888 20.524c.938-1.982.769-6.258.487-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .555.15l.116-.263a.184.184 0 0 1 .226-.099a.176.176 0 0 1 .12.201c-.061.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1d2xybku {
  d: path("M12.941 11.61a3.059 3.059 0 0 1 6.118 0v4.442a.094.094 0 0 1-.094.094h-5.93a.094.094 0 0 1-.094-.094z");
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ero-lfszg {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.792 7.228a.114.114 0 0 0-.013-.144a.12.12 0 0 0-.142-.024a1.3 1.3 0 0 1-.616.146c-.225 0-.437-.053-.614-.146a.12.12 0 0 0-.144.025a.11.11 0 0 0-.012.144m1.541 0L16.75 7.2l.042.027Zm0 0a.92.92 0 0 1-.77.411a.92.92 0 0 1-.77-.411m0 0l.04-.028m-.04.028h-.001l.042-.028m0 0c.154.233.423.39.729.39a.87.87 0 0 0 .728-.39c.04-.06-.028-.128-.09-.096a1.4 1.4 0 0 1-.639.15c-.233 0-.453-.054-.637-.15c-.063-.032-.131.039-.091.096Z");
}

.et-r-fdsf {
  d: path("M11.533 12.744c.486-2.254 1.628-3.333 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.12");
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f283vybwl {
  stop-color: var(--svg-color--8d434a, #8D434A);
  stop-opacity: 0;
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f7w9xyx3p {
  stop-color: var(--svg-color--4475d1, #4475D1);
  stop-opacity: 0;
}

.fkee40m0y {
  stop-color: var(--svg-color--8f5d78, #8F5D78);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.g7lbglbgf {
  fill: var(--svg-color--3b97db, #3B97DB);
  d: path("M11.533 12.744c.486-2.254 1.628-3.333 3.03-3.829v3.95H11.63a.1.1 0 0 1-.098-.12");
}

.gek68lb2e {
  fill: var(--svg-color--4fa0f0, #4FA0F0);
  d: path("M20.468 12.744c-.487-2.254-1.629-3.333-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.12");
}

.gu19b_bxx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.996 5.368c.029.039-.032.087-.102.139s-.121.088-.15.05c-.03-.04.003-.114.073-.166s.15-.062.179-.023");
}

.ha_-8_b3a {
  stop-color: var(--svg-color--97686b, #97686B);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.hj6fgb6dy {
  fill: var(--svg-color--000, #000);
  d: path("M16.79 5.692c0-.13.105-.235.236-.235a.234.234 0 0 1 .209.343h-.417a.2.2 0 0 1-.028-.108");
}

.hpe4_756h {
  stop-color: var(--svg-color--856988, #856988);
  stop-opacity: 0;
}

.hv6ftmbbs {
  d: path("M15.015 5.28a.41.41 0 0 0-.396.52h.794a.414.414 0 0 0-.398-.52");
}

.i-9s0ybju {
  d: path("M17.026 5.281a.41.41 0 0 1 .396.52h-.794a.412.412 0 0 1 .398-.52");
}

.i5n762bmp {
  d: path("m18.24 2.832l.198.098c.346.172.543.565.47.982l-.272 1.4c-.025.145-.12.242-.264.246h-.008s.025-.418.05-.663c.02-.2-.015-.26-.198-.442a.58.58 0 0 1-.173-.393v-.393a.265.265 0 0 0-.198-.246c-.296-.073-.914-.196-1.803-.196s-1.506.123-1.803.196a.24.24 0 0 0-.197.246v.393a.49.49 0 0 1-.173.393l-.074.073c-.1.074-.149.221-.149.344c.025.27.05.663.05.663h-.023a.29.29 0 0 1-.273-.245l-.272-1.4a.94.94 0 0 1 .494-.958l.197-.098c.124-.074.247-.172.37-.27l.445-.467a.9.9 0 0 1 1.013-.147c.247.073.519.073.766 0a1.11 1.11 0 0 1 1.087.245l.37.369c.099.123.222.196.37.27");
}

.imz-u4bms {
  cx: 18.216px;
  cy: 5.815px;
  r: 0.458px;
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.izcj2zmqt {
  fill: var(--svg-color--8f5f62, #8F5F62);
  d: path("M19.333 19.244a.22.22 0 0 0 .043-.239h.437l-.32.996c-.262.078-.54.051-.59-.113a.32.32 0 0 1 .074-.3c.083-.078.271-.254.355-.344");
}

.j6ndfp4vo {
  stop-color: var(--svg-color--6a597b, #6A597B);
  stop-opacity: 0;
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jewrngbdz {
  stop-color: var(--svg-color--b06e67, #B06E67);
  stop-opacity: 0;
}

.jm3khdb3g {
  stop-color: var(--svg-color--a17e7a, #A17E7A);
}

.kcjik5o6k {
  stop-color: var(--svg-color--6a597b, #6A597B);
}

.kdvk3hv7t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.786 4.496c.198-.035.584-.025.852.183");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kl0728zpw {
  stop-color: var(--svg-color--3686df, #3686DF);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lw7z9gbtl {
  stop-color: var(--svg-color--499de8, #499DE8);
  stop-opacity: 0;
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m6qbpgbhr {
  cx: 18.216px;
  cy: 5.815px;
  r: 0.458px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.m85-u4b_v {
  stop-color: var(--svg-color--2c7cd5, #2C7CD5);
  stop-opacity: 0;
}

.m8gz-0b5a {
  d: path("M12.112 20.524c-.938-1.982-.769-6.258-.488-7.823h1.672c-.071 2.425.04 5.243.178 6.511c.011.103.084.214 0 .276a.29.29 0 0 1-.438-.115l-.117-.263a.184.184 0 0 0-.226-.099a.176.176 0 0 0-.12.201c.061.3.172.678.265.973a.42.42 0 0 1-.239.513c-.186.076-.401.008-.487-.174");
}

.m9k7mpbqe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.935 3.6v.413c-.004.068-.033.221-.12.286");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mj9v0bbqu {
  d: path("M13.647 4.87c0-.123.049-.27.148-.344l.074-.073a.49.49 0 0 0 .173-.393v-.393a.24.24 0 0 1 .197-.246a7.6 7.6 0 0 1 1.803-.196c.89 0 1.507.123 1.803.196a.265.265 0 0 1 .198.246v.393c0 .147.074.295.173.393c.23.162.216.25.197.442c-.024.245-.05.663-.05.663h.01L18.25 7.38c-.074.815-.715 1.383-1.478 1.383h-1.479c-.788 0-1.404-.568-1.478-1.383c-.064-.836-.092-1.675-.168-2.51");
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mwrvsh4-t {
  stop-color: var(--svg-color--3b70d0, #3B70D0);
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nb4vlrbxr {
  stop-color: var(--svg-color--4656b3, #4656B3);
}

.nlrjo9pll {
  cx: 14.891px;
  cy: 5.456px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.179px;
  ry: 0.091px;
}

.nrk1uwb9l {
  stop-color: var(--svg-color--8e4a4a, #8E4A4A);
}

.nwf629gla {
  stop-color: var(--svg-color--5ba1d3, #5BA1D3);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.ob07l54eq {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m17.734 4.562l-.001-.001l-.003-.002l-.005-.004l-.071-.05a1.3 1.3 0 0 0-.88-.17a.246.246 0 1 0 .076.486a.8.8 0 0 1 .543.1l.029.02a.246.246 0 0 0 .312-.379");
}

.ob3p6mbly {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.92 5.156a.64.64 0 0 0-.624.487c-.02.08.04.157.123.157h1.027c.066 0 .118-.06.105-.125a.645.645 0 0 0-.632-.52");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofbrbub6c {
  stroke: var(--svg-color--bd8a7d, #BD8A7D);
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M19.813 12.581c.125 1 .3 3.575 0 5.875");
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.oi8jickna {
  d: path("M20.468 12.744c-.487-2.254-1.629-3.333-3.03-3.829v3.95h2.932a.1.1 0 0 0 .098-.12");
}

.ozpey3bvw {
  d: path("m17.847 3.225l-1.418.472a.482.482 0 0 0 .217.936l1.409-.189z");
}

.p07i09slr {
  d: path("m13.016 16.095l.484 12.453h2l.238-9.523c0-.328.029-.86.262-.86c.212 0 .263.555.262.86l.238 9.523h2l.484-12.453z");
}

.p56j8ub-b {
  stop-color: var(--svg-color--39779b, #39779B);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pm40e6_le {
  stop-color: var(--svg-color--3a87b0, #3A87B0);
}

.q7l1h8mqg {
  stop-color: var(--svg-color--9e6774, #9E6774);
  stop-opacity: 0;
}

.qi8gzubuf {
  cx: 14.891px;
  cy: 5.456px;
  rx: 0.179px;
  ry: 0.091px;
}

.qlcrdsbcc {
  d: path("M15.129 7.458h1.742V8.81a.871.871 0 0 1-1.742 0z");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qnuhplbln {
  stop-color: var(--svg-color--635185, #635185);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxmupoqkj {
  d: path("M15.39 5.644c0-.133-.108-.222-.137-.248l-.133.128l.082.166z");
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.qzjv9wb_n {
  fill: var(--svg-color--87565c, #87565C);
  d: path("m15.895 5.758l-.378.783c-.047.16.066.322.225.322h.34c.159 0 .27-.164.224-.322l-.23-.783c-.049-.173-.13-.173-.181 0");
}

.rsfoz3blw {
  stop-color: var(--svg-color--5ba1d3, #5BA1D3);
  stop-opacity: 0;
}

.sb3cb-bog {
  stop-color: var(--svg-color--856988, #856988);
}

.sc4il2d7k {
  stop-color: var(--svg-color--3270c8, #3270C8);
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t9px69bkt {
  fill: var(--svg-color--bb937c, #BB937C);
  d: path("M19.888 20.524c.938-1.982.769-6.258.487-7.823h-1.671c.071 2.425-.156 5.253-.294 6.522a.29.29 0 0 0 .555.15l.116-.263a.184.184 0 0 1 .226-.099a.176.176 0 0 1 .12.201c-.061.3-.172.678-.265.973a.42.42 0 0 0 .239.513c.186.076.401.008.487-.174");
}

.tb5vgbckn {
  stop-color: var(--svg-color--2680e1, #2680E1);
  stop-opacity: 0;
}

.to0orccvb {
  stop-color: var(--svg-color--2680e1, #2680E1);
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tpb8kfbdc {
  stop-color: var(--svg-color--3b70cf, #3B70CF);
  stop-opacity: 0;
}

.u_3hhfbdm {
  stop-color: var(--svg-color--4db7f8, #4DB7F8);
}

.u0xg32bgc {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.121 5.156c.3 0 .555.207.624.487a.126.126 0 0 1-.123.157h-1.028a.106.106 0 0 1-.104-.125a.644.644 0 0 1 .631-.52");
}

.u5jeodkbz {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m14.284 4.562l.002-.001l.002-.002l.005-.004l.072-.05a1.3 1.3 0 0 1 .88-.17a.246.246 0 0 1-.077.486a.8.8 0 0 0-.543.1l-.025.018l-.003.003a.246.246 0 0 1-.313-.38");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.voaf13bac {
  stop-color: var(--svg-color--3b70cf, #3B70CF);
}

.w_7sj9bks {
  d: path("M13.673 5.533h.023s-.025-.393-.05-.663c0-.123.05-.27.149-.344l.074-.073a.49.49 0 0 0 .173-.393v-.393a.24.24 0 0 1 .197-.246a7.6 7.6 0 0 1 1.803-.196c.89 0 1.507.123 1.803.196a.265.265 0 0 1 .198.246v.393c0 .147.074.295.173.393c.23.162.216.25.197.442c-.024.245-.05.663-.05.663h.01L18.25 7.38c-.074.815-.715 1.383-1.478 1.383h-1.479c-.788 0-1.404-.568-1.478-1.383z");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.w48qw8bka {
  stop-color: var(--svg-color--8d5460, #8D5460);
}

.wa3nobd_c {
  fill: var(--svg-color--5d4480, #5D4480);
  d: path("M12.434 29.904v.242H15.5v-1.598h-1.992c-.102.367-.574.754-.817.914a.54.54 0 0 0-.257.442");
}

.wma78obnb {
  cx: 13.835px;
  cy: 5.815px;
  r: 0.769px;
}

.wpolc4b9j {
  fill: var(--svg-color--000, #000);
  d: path("M15.25 5.692a.234.234 0 0 0-.235-.235a.234.234 0 0 0-.21.343h.417a.23.23 0 0 0 .028-.108");
}

.wwbz7ibcz {
  stop-color: var(--svg-color--462f5e, #462F5E);
}

.wxdu2lj0o {
  d: path("m17.734 4.562l-.001-.001l-.003-.002l-.005-.004l-.071-.05a1.3 1.3 0 0 0-.88-.17a.246.246 0 1 0 .076.486a.8.8 0 0 1 .543.1l.029.02a.246.246 0 0 0 .312-.379");
}

.wz3lzhbxc {
  stop-color: var(--svg-color--49a1f7, #49A1F7);
  stop-opacity: 0;
}

.x7tdxqavt {
  stop-color: var(--svg-color--aa9ba7, #AA9BA7);
}

.x92fm7bvu {
  d: path("M19.566 29.904v.242H16.5v-1.598h1.992c.102.367.574.754.817.914a.54.54 0 0 1 .257.442");
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.y_mkc7b6b {
  fill: var(--svg-color--794a4d, #794A4D);
  d: path("M12.668 19.244a.22.22 0 0 1-.043-.239h-.438l.32.996c.262.078.54.051.59-.113a.32.32 0 0 0-.074-.3a9 9 0 0 1-.355-.344");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.ywr6uvbgg {
  d: path("m14.284 4.562l.002-.001l.002-.002l.005-.004l.072-.05a1.3 1.3 0 0 1 .88-.17a.246.246 0 0 1-.077.486a.8.8 0 0 0-.543.1l-.025.018l-.003.003a.246.246 0 0 1-.313-.38");
}

.z3z2fqbpi {
  stop-color: var(--svg-color--635185, #635185);
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zay0pib-e {
  stop-color: var(--svg-color--8d434a, #8D434A);
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>

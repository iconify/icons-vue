<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iD0Idee)" transform="rotate(39.16 14.713 7.746)" class="uqr5of0zr"/><path fill="url(#iSIuUDe)" class="b0-a-ii1x"/><g filter="url(#icRLDjd)"><path fill="url(#idzWydb)" class="cw7je1byy"/><path fill="url(#ic47kkc)" class="cw7je1byy"/><path fill="url(#iZ7zMCe)" class="cw7je1byy"/></g><path clip-rule="evenodd" class="rzylvmb3f"/><g filter="url(#iFFzrJe)"><path clip-rule="evenodd" class="mk68h67wx"/></g><g filter="url(#iN3yidc)"><path fill="url(#iFlmEPc)" class="lcj6z75gw"/><path fill="url(#iNaR3xX)" class="lcj6z75gw"/></g><path fill="url(#iyxbLZb)" class="eho0-pbqh"/><g filter="url(#i11Fw3c)"><path class="vy4n1ruvh"/><path fill="url(#i2pcVSb)" class="giwgxhb5d"/></g><path fill="url(#ie69lHb)" class="wd54n2b7e"/><path fill="url(#i4kkFAc)" class="bxhu-ibkw"/><path fill="url(#in0ItGd)" class="bxhu-ibkw"/><path fill="url(#iGYZA6b)" class="bxhu-ibkw"/><path fill="url(#iX6g4Fc)" class="bxhu-ibkw"/><g filter="url(#ii2ktne)"><path fill="url(#iJkxNJe)" class="gdejg6bni"/><path fill="url(#iKZzlPe)" class="gdejg6bni"/><path fill="url(#i1T4qOM)" class="gdejg6bni"/></g><g filter="url(#iuD5Kje)"><rect fill="url(#i4VhV6b)" class="nfr827qhb"/><rect fill="url(#iiaEOtQ)" class="nfr827qhb"/><rect fill="url(#iYubhjc)" class="nfr827qhb"/><rect fill="url(#iToyIIc)" class="nfr827qhb"/></g><rect fill="url(#iOCpd5v)" transform="rotate(-21.787 19.523 13.104)" class="cw0h2acjt"/><path fill="url(#icuBxib)" class="of061phyp"/><path fill="url(#iol3JCb)" class="of061phyp"/><path fill="url(#izuaCxe)" class="of061phyp"/><g filter="url(#iUNh4nb)"><path fill="url(#iuW8Liv)" class="x4qda34vb"/></g><g filter="url(#il6jtQW)"><path fill="url(#i34eBDc)" class="jdui8ilgj"/><path fill="url(#iAvM3yd)" class="jdui8ilgj"/><path fill="url(#iH1gSYh)" class="jdui8ilgj"/></g><g filter="url(#ipbZusb)"><path class="wpvfuacxk"/><path fill="url(#iWvpV2c)" class="y7_jp-bjv"/></g><g filter="url(#iGIeJZc)"><path stroke="url(#i0YHoCc)" class="sc6ogxblv"/></g><g filter="url(#iHcsvlc)"><path fill="url(#iEe6m6d)" class="i3hca91-d"/></g><path class="e3y6lq78v"/><path fill="url(#ij28tuP)" class="w33p5rbaf"/><path fill="url(#i2pjPLd)" class="ppyxirbrj"/><path class="u6rwk2z-u"/><defs><radialGradient id="iD0Idee" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.303 9.676)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="vcu64j97k"/><stop offset="1" class="gunhc6l2n"/></radialGradient><radialGradient id="iSIuUDe" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.248 10.542)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="h3zh53qvw"/><stop offset="1" class="fi90oja5q"/></radialGradient><radialGradient id="idzWydb" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.17 5.299)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="r-d7trp-i"/><stop offset="1" class="r6qq21ggw"/></radialGradient><radialGradient id="ic47kkc" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.856 10.206)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="f1i_yegdv"/><stop offset="1" class="u88gs8tgg"/></radialGradient><radialGradient id="iZ7zMCe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.14)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="ckhkjqgwn"/><stop offset="1" class="qji6614xa"/></radialGradient><radialGradient id="iFlmEPc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31333 1.068 -1.15703 -4.67289 18.613 5.73)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="vercztyxt"/><stop offset="1" class="liqt-9bwf"/></radialGradient><radialGradient id="iNaR3xX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.09453 1.35194 0 14.823 6.916)" gradientUnits="userSpaceOnUse"><stop class="b9y4twush"/><stop offset="1" class="aqxf-er5e"/></radialGradient><radialGradient id="iyxbLZb" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 6.973)" gradientUnits="userSpaceOnUse"><stop class="fdu6h3mkt"/><stop offset="1" class="xupjr2xdh"/></radialGradient><radialGradient id="i2pcVSb" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.076 15.261)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ynstgccdl"/><stop offset="1" class="ph7rypboq"/></radialGradient><radialGradient id="ie69lHb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.28 48.674)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iGYZA6b" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.067)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iX6g4Fc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.973)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iJkxNJe" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.211 15.111)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iKZzlPe" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.9 10.427)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="i1T4qOM" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.16)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iiaEOtQ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.192)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="iYubhjc" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.663)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iToyIIc" cx="0" cy="0" r="1" gradientTransform="rotate(90 .757 17.2)scale(.8125 9.78126)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="iOCpd5v" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.364)" gradientUnits="userSpaceOnUse"><stop class="sl7x9k6lz"/><stop offset="1" class="mhva3mbnf"/></radialGradient><radialGradient id="icuBxib" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.305 10.79)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iuW8Liv" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21.005)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="iAvM3yd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.973)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iWvpV2c" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.952)" gradientUnits="userSpaceOnUse"><stop class="p1w13ebbm"/><stop offset="1" class="tiuzwhbbw"/></radialGradient><radialGradient id="iEe6m6d" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="v0g3nqbgo"/><stop offset="1" class="mcj2tdbkt"/></radialGradient><radialGradient id="ij28tuP" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.8)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="i2pjPLd" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.536)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="icRLDjd" width="4.17" height="4.439" x="14.414" y="5.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.25098 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="iFFzrJe" width=".763" height=".367" x="17.245" y="6.633" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0705882 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="iN3yidc" width="5.17" height="3.72" x="13.955" y="4.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0470588 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="i11Fw3c" width="6.377" height="6.141" x="9.574" y="8.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.447059 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.447059 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23069" result="effect2_innerShadow_3987_23069"/></filter><filter id="ii2ktne" width="27.983" height="6.037" x="2.059" y="20.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="iuD5Kje" width="24.059" height="2.191" x="3.886" y="15.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="iUNh4nb" width="6.802" height="6.803" x="8.337" y="19.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="il6jtQW" width="27.983" height="6.037" x="1.959" y="24.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="ipbZusb" width="6.678" height="4.108" x="14.785" y="10.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.286275 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><filter id="iGIeJZc" width="5.181" height="3.008" x="14.805" y="11.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23069" stdDeviation=".2"/></filter><filter id="iHcsvlc" width="3.882" height="3.705" x="12.803" y="9.292" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.392157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23069"/></filter><linearGradient id="i4kkFAc" x1="25.051" x2="7.801" y1="18.911" y2="24.286" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="in0ItGd" x1="27.145" x2="26.441" y1="20.473" y2="20.473" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="i4VhV6b" x1="16.015" x2="16.395" y1="15.317" y2="18.848" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="iol3JCb" x1="17.168" x2="17.582" y1="16.352" y2="16.747" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="izuaCxe" x1="19.52" x2="19.184" y1="16.036" y2="15.684" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="i34eBDc" x1="18.457" x2="12.738" y1="23.442" y2="33.536" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="iH1gSYh" x1="18.02" x2="18.02" y1="30.005" y2="29.723" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="i0YHoCc" x1="15.734" x2="20.015" y1="12.297" y2="14.015" gradientUnits="userSpaceOnUse"><stop class="ul9idmbej"/><stop offset="1" class="w86a2obti"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-rowing-boat-medium-dark" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.aqxf-er5e {
  stop-color: var(--svg-color--3c3231, #3C3231);
  stop-opacity: 0;
}

.b0-a-ii1x {
  d: path("M18.232 8.102c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.139.515-.031c.098-.122.079-.301-.023-.485");
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.b9y4twush {
  stop-color: var(--svg-color--3c3231, #3C3231);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.bxhu-ibkw {
  d: path("m5.232 17.026l21.725-.021v6.25l-18.008-.118z");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.ckhkjqgwn {
  stop-color: var(--svg-color--926d66, #926D66);
}

.cw0h2acjt {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.104px;
  rx: 0.318px;
}

.cw7je1byy {
  d: path("M15.931 9.707a4.2 4.2 0 0 1-1.203-.91c-.38-.408-.386-1-.172-1.514l.327-.786a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.182.576.644.369 1.475c-.229 1.081-.501 1.744-.749 2.227c-.177.344-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.dzuixsuao {
  stop-color: var(--svg-color--55beff, #55BEFF);
  stop-opacity: 0;
}

.e_s-6on8g {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
  stop-opacity: 0;
}

.e21-2rm4b {
  stop-color: var(--svg-color--659941, #659941);
}

.e3y6lq78v {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.823c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.278l-.003.01c-.015.059.01.118.066.133z");
}

.eho0-pbqh {
  d: path("M15.919 6.616a.625.625 0 0 0-.373 1.175z");
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.f1i_yegdv {
  stop-color: var(--svg-color--9a796d, #9A796D);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fdu6h3mkt {
  stop-color: var(--svg-color--8c6b64, #8C6B64);
}

.fi90oja5q {
  stop-color: var(--svg-color--7c5741, #7C5741);
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gdejg6bni {
  d: path("M3.504 20.989c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.giwgxhb5d {
  d: path("M11.168 10.614c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.gunhc6l2n {
  stop-color: var(--svg-color--754f43, #754F43);
}

.h3zh53qvw {
  stop-color: var(--svg-color--8d6e63, #8D6E63);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.i3hca91-d {
  d: path("M13.004 11.114c.6.719 1.333 1.555 1.625 1.883l1.656-1.485c-.33-.396-1.117-1.303-1.617-1.765c-.625-.578-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jdui8ilgj {
  d: path("M3.504 24.489c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.lcj6z75gw {
  d: path("M13.992 7.298c-.16-1.207.231-2.071.46-2.418a.98.98 0 0 1 .867-.515c.324-.004.493.168.75.12c.103-.018.474-.155.77.028c.246.153.445.235.605.235c.227 0 .557-.045.797.3c.25.36.543.332.695.575s.137.773-.277.968c-.414.196-1.313-.21-1.641-.343s-.55-.075-.752.246c-.163.256-.462.31-.592.316c-.093.193-.307.696-.61.992c-.322.317-1 .035-1.072-.504");
}

.liqt-9bwf {
  stop-color: var(--svg-color--281a23, #281A23);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mcj2tdbkt {
  stop-color: var(--svg-color--397bd7, #397BD7);
}

.mhva3mbnf {
  stop-color: var(--svg-color--76594d, #76594D);
}

.mk68h67wx {
  fill: var(--svg-color--453a3a, #453A3A);
  fill-rule: evenodd;
  d: path("M17.866 6.99a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.nfr827qhb {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.568px;
  rx: 1.095px;
}

.of061phyp {
  d: path("M21.334 12.32a.59.59 0 0 1 .829.839l-8.439 8.331a.59.59 0 1 1-.829-.84z");
}

.p1w13ebbm {
  stop-color: var(--svg-color--977970, #977970);
}

.ph7rypboq {
  stop-color: var(--svg-color--275dc4, #275DC4);
  stop-opacity: 0;
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.ppyxirbrj {
  d: path("M17.641 7.822q.045-.05.061-.11c.027-.099-.019-.206-.097-.227c-.08-.02-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.qji6614xa {
  stop-color: var(--svg-color--926d66, #926D66);
  stop-opacity: 0;
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r-d7trp-i {
  stop-color: var(--svg-color--8f695d, #8F695D);
}

.r6qq21ggw {
  stop-color: var(--svg-color--81534e, #81534E);
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.rzylvmb3f {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.511a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.sc6ogxblv {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.359 11.766c.291.348.889.87 1.804 1.164c1.438.46 1.735.515 2.36.726");
}

.sl7x9k6lz {
  stop-color: var(--svg-color--81675e, #81675E);
}

.tiuzwhbbw {
  stop-color: var(--svg-color--977970, #977970);
  stop-opacity: 0;
}

.u6rwk2z-u {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.451c.016-.036.07-.048.119-.026s.075.07.059.106c-.017.036-.07.048-.119.026s-.075-.07-.059-.106");
}

.u88gs8tgg {
  stop-color: var(--svg-color--9a796d, #9A796D);
  stop-opacity: 0;
}

.ul9idmbej {
  stop-color: var(--svg-color--957168, #957168);
}

.uqr5of0zr {
  d: path("M14.713 7.746h1.744v2h-1.744z");
}

.v0g3nqbgo {
  stop-color: var(--svg-color--579ff0, #579FF0);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.vcu64j97k {
  stop-color: var(--svg-color--683a26, #683A26);
}

.vercztyxt {
  stop-color: var(--svg-color--372228, #372228);
}

.vy4n1ruvh {
  fill: var(--svg-color--338ae5, #338AE5);
  d: path("M11.168 10.614c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.w33p5rbaf {
  d: path("M17.72 7.844c.02-.037.038-.064.051-.113c.048-.178-.02-.355-.169-.394c-.138-.037-.296.079-.343.256a.5.5 0 0 0-.012.124z");
}

.w86a2obti {
  stop-color: var(--svg-color--957168, #957168);
  stop-opacity: 0;
}

.wd54n2b7e {
  d: path("M9.598 13.77c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.wpvfuacxk {
  fill: var(--svg-color--886657, #886657);
  d: path("M16.504 13.825c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.x4qda34vb {
  d: path("M11.366 20.368a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.711z");
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xupjr2xdh {
  stop-color: var(--svg-color--7f594f, #7F594F);
}

.y7_jp-bjv {
  d: path("M16.504 13.825c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.ynstgccdl {
  stop-color: var(--svg-color--275dc4, #275DC4);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>

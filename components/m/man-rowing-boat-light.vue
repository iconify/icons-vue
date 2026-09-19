<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iRdrDGd)" transform="rotate(39.16 14.713 7.843)" class="ika1-2y1s"/><path fill="url(#iJcb3Ab)" class="db46b5bpu"/><g filter="url(#iriPvmd)"><path fill="url(#iEacZNc)" class="sf3h2db9m"/><path fill="url(#iCJknUc)" class="sf3h2db9m"/><path fill="url(#iTTlbOb)" class="sf3h2db9m"/></g><path clip-rule="evenodd" class="b_vuuhbys"/><g filter="url(#iVEE6Zc)"><path clip-rule="evenodd" class="j_ni4db7c"/></g><g filter="url(#icJb2cb)"><path fill="url(#iV6YhGe)" class="skw-zob5o"/><path fill="url(#i1V9JDb)" class="skw-zob5o"/></g><path fill="url(#iP1Yhfb)" class="juxqywwgb"/><g filter="url(#ieV74ht)"><path class="hkm_f2bcr"/><path fill="url(#iGUQOOb)" class="n4kwkl70m"/></g><path fill="url(#ifKdFpb)" class="hec337bhq"/><path fill="url(#iOY3nSd)" class="byj_tusbv"/><path fill="url(#i7Z3auf)" class="byj_tusbv"/><path fill="url(#ir7mOzb)" class="byj_tusbv"/><path fill="url(#idcv5MZ)" class="byj_tusbv"/><g filter="url(#iGiR4By)"><path fill="url(#iUVFBcJ)" class="p6lsn1bwm"/><path fill="url(#iDzhVjH)" class="p6lsn1bwm"/><path fill="url(#i0ioFLd)" class="p6lsn1bwm"/></g><g filter="url(#iWKGs4b)"><rect fill="url(#ibeqGmc)" class="xi79cqbov"/><rect fill="url(#i5jKrPK)" class="xi79cqbov"/><rect fill="url(#ia7G8VW)" class="xi79cqbov"/><rect fill="url(#iqg8wwe)" class="xi79cqbov"/></g><rect fill="url(#iKIX5jc)" transform="rotate(-21.787 19.523 13.2)" class="ldmnoc93z"/><path fill="url(#iejlYNR)" class="axttkhfcf"/><path fill="url(#i0r1ukd)" class="axttkhfcf"/><path fill="url(#iPXB77c)" class="axttkhfcf"/><g filter="url(#igIkYfe)"><path fill="url(#im3ByDd)" class="g7sct8b3c"/></g><g filter="url(#i0y9kZA)"><path fill="url(#iwBGalc)" class="r1-az1qrd"/><path fill="url(#irMrJZd)" class="r1-az1qrd"/><path fill="url(#ikMi4Ej)" class="r1-az1qrd"/></g><g filter="url(#iK8jvyd)"><path class="quflseb1q"/><path fill="url(#icff89V)" class="y0hharb9q"/></g><g filter="url(#i4uiXYG)"><path stroke="url(#iUcTWqd)" class="m9v4hdc5g"/></g><g filter="url(#i7L7ZTc)"><path fill="url(#iuTXrex)" class="c_5ecfb8v"/></g><path class="xftfdvbvg"/><path fill="url(#iYECTTf)" class="aseyjjvwp"/><path fill="url(#i8PjAJe)" class="err7mcn4l"/><path class="c47dd0b6a"/><defs><radialGradient id="iRdrDGd" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.27 9.725)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="ztkiyibrv"/><stop offset="1" class="bp2cggfyk"/></radialGradient><radialGradient id="iJcb3Ab" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.213 10.59)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="t04vb-hcs"/><stop offset="1" class="kguf3qbxw"/></radialGradient><radialGradient id="iEacZNc" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.161 5.347)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="az2qiyawh"/><stop offset="1" class="t4coan9us"/></radialGradient><radialGradient id="iCJknUc" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.82 10.254)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="q2qi1lbnq"/><stop offset="1" class="kpwscabck"/></radialGradient><radialGradient id="iTTlbOb" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.237)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="q2qi1lbnq"/><stop offset="1" class="kpwscabck"/></radialGradient><radialGradient id="iV6YhGe" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31333 1.068 -1.15703 -4.67289 18.613 5.826)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="j9b-420yy"/><stop offset="1" class="k5y4d_b1p"/></radialGradient><radialGradient id="i1V9JDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.09453 1.35194 0 14.823 7.013)" gradientUnits="userSpaceOnUse"><stop class="yte4k7nua"/><stop offset="1" class="h846rykft"/></radialGradient><radialGradient id="iP1Yhfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 7.07)" gradientUnits="userSpaceOnUse"><stop class="sx736obft"/><stop offset="1" class="sx736obft"/></radialGradient><radialGradient id="iGUQOOb" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.142 15.31)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ynstgccdl"/><stop offset="1" class="ph7rypboq"/></radialGradient><radialGradient id="ifKdFpb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.644 48.723)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="ir7mOzb" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.164)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="idcv5MZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 22.07)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iUVFBcJ" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.19 15.16)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iDzhVjH" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.922 10.475)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="i0ioFLd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.257)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="i5jKrPK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.289)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="ia7G8VW" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.76)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iqg8wwe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.539)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="iKIX5jc" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.461)" gradientUnits="userSpaceOnUse"><stop class="mwy-f8bpu"/><stop offset="1" class="ejqwb0bqm"/></radialGradient><radialGradient id="iejlYNR" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.285 10.84)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="im3ByDd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21.101)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="irMrJZd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 29.07)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="icff89V" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29688 .16254 .33364 20.747 14.05)" gradientUnits="userSpaceOnUse"><stop class="n4xk4fb0e"/><stop offset="1" class="co6663b7r"/></radialGradient><radialGradient id="iuTXrex" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.289)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="v0g3nqbgo"/><stop offset="1" class="mcj2tdbkt"/></radialGradient><radialGradient id="iYECTTf" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.898)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="i8PjAJe" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.632)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="iriPvmd" width="4.17" height="4.439" x="14.414" y="5.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.572549 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="iVEE6Zc" width=".763" height=".367" x="17.245" y="6.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0196078 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="icJb2cb" width="5.17" height="3.72" x="13.955" y="4.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0588235 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="ieV74ht" width="6.377" height="6.141" x="9.574" y="9.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.447059 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.447059 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23078" result="effect2_innerShadow_3987_23078"/></filter><filter id="iGiR4By" width="27.983" height="6.037" x="2.059" y="20.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="iWKGs4b" width="24.059" height="2.191" x="3.886" y="15.664" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="igIkYfe" width="6.802" height="6.803" x="8.337" y="19.403" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="i0y9kZA" width="27.983" height="6.037" x="1.959" y="24.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="iK8jvyd" width="6.678" height="4.108" x="14.785" y="10.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><filter id="i4uiXYG" width="5.181" height="3.008" x="14.805" y="11.334" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23078" stdDeviation=".2"/></filter><filter id="i7L7ZTc" width="3.882" height="3.705" x="12.803" y="9.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.392157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23078"/></filter><linearGradient id="iOY3nSd" x1="25.051" x2="7.801" y1="19.007" y2="24.382" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="i7Z3auf" x1="27.145" x2="26.441" y1="20.57" y2="20.57" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="ibeqGmc" x1="16.015" x2="16.395" y1="15.414" y2="18.945" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="i0r1ukd" x1="17.168" x2="17.582" y1="16.449" y2="16.843" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iPXB77c" x1="19.52" x2="19.184" y1="16.132" y2="15.781" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="iwBGalc" x1="18.457" x2="12.738" y1="23.539" y2="33.632" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ikMi4Ej" x1="18.02" x2="18.02" y1="30.101" y2="29.82" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iUcTWqd" x1="15.734" x2="20.015" y1="12.393" y2="14.112" gradientUnits="userSpaceOnUse"><stop class="u_4uylzec"/><stop offset="1" class="yauhuibbl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-rowing-boat-light" /></template>
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

.aseyjjvwp {
  d: path("M17.72 7.94c.02-.036.038-.063.051-.113c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.124z");
}

.axttkhfcf {
  d: path("M21.334 12.416a.59.59 0 1 1 .829.84l-8.439 8.33a.59.59 0 0 1-.829-.839z");
}

.az2qiyawh {
  stop-color: var(--svg-color--fac4b1, #FAC4B1);
}

.b_vuuhbys {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.608a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.426a.1.1 0 0 1 .05-.132");
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.bp2cggfyk {
  stop-color: var(--svg-color--e8a28d, #E8A28D);
}

.byj_tusbv {
  d: path("m5.232 17.123l21.725-.022v6.25l-18.008-.117z");
}

.c_5ecfb8v {
  d: path("M13.004 11.21a93 93 0 0 0 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.303-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.688-.195 1.368");
}

.c47dd0b6a {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.548c.016-.037.07-.049.119-.027s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.106");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.co6663b7r {
  stop-color: var(--svg-color--f7cfbd, #F7CFBD);
  stop-opacity: 0;
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.db46b5bpu {
  d: path("M18.232 8.199c-.081-.147-.066-.412-.047-.504l-.445 1.02c.14.074.378.139.515-.032c.098-.12.079-.3-.023-.484");
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

.ejqwb0bqm {
  stop-color: var(--svg-color--d9ad92, #D9AD92);
}

.err7mcn4l {
  d: path("M17.641 7.919q.045-.051.061-.11c.027-.099-.019-.206-.097-.227c-.08-.021-.17.039-.198.147a.3.3 0 0 0-.002.126z");
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g7sct8b3c {
  d: path("M11.366 20.464a1.917 1.917 0 0 1 2.712 2.711l-2.468 2.469a1.917 1.917 0 1 1-2.712-2.71z");
}

.h846rykft {
  stop-color: var(--svg-color--48403e, #48403E);
  stop-opacity: 0;
}

.hec337bhq {
  d: path("M9.598 13.867c-.243.894-.203 1.761-.11 2.023l6.309-.062z");
}

.hkm_f2bcr {
  fill: var(--svg-color--338ae5, #338AE5);
  d: path("M11.168 10.71c-1.006 1.232-1.414 2.669-1.594 3.274l3.992 1.25c.125-1.024.75-2.719 1.172-3.375s.489-.871.555-1.348c.066-.476-.256-1.194-1.336-1.394c-.844-.157-1.854.45-2.789 1.593");
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ika1-2y1s {
  d: path("M14.713 7.843h1.744v2h-1.744z");
}

.j_ni4db7c {
  fill: var(--svg-color--323232, #323232);
  fill-rule: evenodd;
  d: path("M17.866 7.087a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.j9b-420yy {
  stop-color: var(--svg-color--2f2529, #2F2529);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.juxqywwgb {
  d: path("M15.919 6.713a.625.625 0 0 0-.373 1.175z");
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k5y4d_b1p {
  stop-color: var(--svg-color--211b1e, #211B1E);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.kguf3qbxw {
  stop-color: var(--svg-color--e7b89f, #E7B89F);
}

.kpwscabck {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
  stop-opacity: 0;
}

.ldmnoc93z {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.201px;
  rx: 0.318px;
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.m9v4hdc5g {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.359 11.862c.291.35.889.87 1.804 1.164c1.438.461 1.735.516 2.36.727");
}

.mcj2tdbkt {
  stop-color: var(--svg-color--397bd7, #397BD7);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mwy-f8bpu {
  stop-color: var(--svg-color--e2b79d, #E2B79D);
}

.n4kwkl70m {
  d: path("M11.168 10.71c-1.006 1.232-1.414 2.669-1.594 3.274l3.992 1.25c.125-1.024.75-2.719 1.172-3.375s.489-.871.555-1.348c.066-.476-.256-1.194-1.336-1.394c-.844-.157-1.854.45-2.789 1.593");
}

.n4xk4fb0e {
  stop-color: var(--svg-color--f7cfbd, #F7CFBD);
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.p6lsn1bwm {
  d: path("M3.504 21.086c-.775-.425-1.254-.422-1.445-.422V26.6H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.102-1.539-.438s-1.324-.703-1.98-.703c-.654 0-1.311.334-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.735");
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

.q2qi1lbnq {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.quflseb1q {
  fill: var(--svg-color--f2c6af, #F2C6AF);
  d: path("M16.504 13.921c-.713-.33-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.11 2.375 1.278 2.684 1.351c.395.094 1.538.301 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.204s-.559-.27-1.227-.399a10 10 0 0 1-2.246-.719");
}

.r1-az1qrd {
  d: path("M3.504 24.586c-.775-.425-1.254-.422-1.445-.422V30.1H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.102-1.539-.438s-1.324-.703-1.98-.703c-.654 0-1.311.334-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.735");
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.sf3h2db9m {
  d: path("M15.931 9.804a4.2 4.2 0 0 1-1.203-.91c-.38-.409-.386-1-.172-1.514l.327-.786a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.003.372.066c.288.183.576.645.369 1.476c-.229 1.08-.501 1.744-.749 2.227c-.177.344-.533.572-.916.505a3.2 3.2 0 0 1-.718-.216");
}

.skw-zob5o {
  d: path("M13.992 7.395c-.16-1.207.231-2.072.46-2.418a.98.98 0 0 1 .867-.516c.324-.003.493.168.75.122c.103-.02.474-.157.77.027c.246.153.445.234.605.234c.227 0 .557-.044.797.301c.25.36.543.332.695.574s.137.774-.277.969s-1.313-.21-1.641-.344s-.55-.074-.752.246c-.163.257-.462.312-.592.317c-.093.192-.307.696-.61.992c-.322.316-1 .035-1.072-.504");
}

.sx736obft {
  stop-color: var(--svg-color--f6c1ac, #F6C1AC);
}

.t04vb-hcs {
  stop-color: var(--svg-color--f4c8b2, #F4C8B2);
}

.t4coan9us {
  stop-color: var(--svg-color--eea894, #EEA894);
}

.u_4uylzec {
  stop-color: var(--svg-color--f7c6b6, #F7C6B6);
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

.xftfdvbvg {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.92c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.051-.434.031-.5.277l-.003.01c-.015.06.01.118.066.134z");
}

.xi79cqbov {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.664px;
  rx: 1.095px;
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.y0hharb9q {
  d: path("M16.504 13.921c-.713-.33-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.11 2.375 1.278 2.684 1.351c.395.094 1.538.301 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.204s-.559-.27-1.227-.399a10 10 0 0 1-2.246-.719");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.yauhuibbl {
  stop-color: var(--svg-color--f7c6b6, #F7C6B6);
  stop-opacity: 0;
}

.ynstgccdl {
  stop-color: var(--svg-color--275dc4, #275DC4);
}

.yte4k7nua {
  stop-color: var(--svg-color--48403e, #48403E);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.ztkiyibrv {
  stop-color: var(--svg-color--d38e77, #D38E77);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>

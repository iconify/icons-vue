<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBWVvRd)" transform="rotate(39.16 14.713 7.6)" class="n61r1nbbs"/><path fill="url(#iikRTCe)" class="mf6h7sjsc"/><g filter="url(#iBz38kc)"><path fill="url(#iU15Htb)" class="adpffqb5u"/></g><path clip-rule="evenodd" class="fqhmacygq"/><g filter="url(#iOZ4xHc)"><path clip-rule="evenodd" class="kkmkysy7w"/></g><g filter="url(#iyXpXOd)"><path fill="url(#iUAtqce)" class="wntbizbps"/></g><path fill="url(#iBBTyXc)" class="bfsiezbmr"/><g filter="url(#ii7BUkd)"><path class="wjlwbzb_i"/><path fill="url(#i8nPnGY)" class="xuvoz5f8s"/></g><path fill="url(#it0zbCc)" class="r-v52zbsa"/><path fill="url(#ipbpqNd)" class="o6qeis12c"/><path fill="url(#iVF7qJc)" class="o6qeis12c"/><path fill="url(#iF77ree)" class="o6qeis12c"/><path fill="url(#iPT1efd)" class="o6qeis12c"/><g filter="url(#i8gcTbe)"><path fill="url(#iqM9XDb)" class="qs775uzcx"/><path fill="url(#i2rnVye)" class="qs775uzcx"/><path fill="url(#iQdwSUb)" class="qs775uzcx"/></g><g filter="url(#ilWJ4Dd)"><rect fill="url(#i50FZvc)" class="ebzms6b8q"/><rect fill="url(#iUOn9Bc)" class="ebzms6b8q"/><rect fill="url(#iZPWVeb)" class="ebzms6b8q"/><rect fill="url(#iv7fJ5d)" class="ebzms6b8q"/></g><g filter="url(#iypfZze)"><rect transform="rotate(-21.787 19.523 12.958)" class="lvejfg9su"/></g><path fill="url(#iN3chWb)" class="imybosvwl"/><path fill="url(#iiy3e4b)" class="imybosvwl"/><path fill="url(#i0Tj1iR)" class="imybosvwl"/><g filter="url(#iY8x9Ee)"><path fill="url(#i6TS28c)" class="ii_74fbyn"/></g><g filter="url(#icdkcCc)"><path fill="url(#iJL2VKr)" class="jge5r9byj"/><path fill="url(#iRnqP1b)" class="jge5r9byj"/><path fill="url(#igmUtie)" class="jge5r9byj"/></g><g filter="url(#iwSVkXd)"><path class="zfmr3z7nq"/></g><g filter="url(#iLZ4gHG)"><path fill="url(#ioy69Uc)" class="hdjy9rbia"/></g><path class="gg_m2zbqv"/><path fill="url(#iu7ttPd)" class="ppjz_ab6v"/><path fill="url(#iYdx4oi)" class="y-c17bb3v"/><path class="v2y4mzboj"/><defs><radialGradient id="iBWVvRd" cx="0" cy="0" r="1" gradientTransform="rotate(125.15 6.095 8.468)scale(1.12391 2.0719)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="lov826b0t"/><stop offset="1" class="fddv1-bhi"/></radialGradient><radialGradient id="iikRTCe" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.3 10.47)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="q8kvbpx8t"/><stop offset="1" class="ez8jvgb-h"/></radialGradient><radialGradient id="iU15Htb" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.18 5.226)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="hj5q0lb4p"/><stop offset="1" class="p0r8r5bwk"/></radialGradient><radialGradient id="iUAtqce" cx="0" cy="0" r="1" gradientTransform="matrix(-4.0736 1.08862 -1.17937 -4.41318 18.613 5.583)" gradientUnits="userSpaceOnUse"><stop class="mxpb4bwvu"/><stop offset="1" class="it6t3x2fl"/></radialGradient><radialGradient id="iBBTyXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 6.827)" gradientUnits="userSpaceOnUse"><stop class="mx8nfvb1t"/><stop offset="1" class="z0ce-5bzk"/></radialGradient><radialGradient id="i8nPnGY" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -.977 15.188)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ynstgccdl"/><stop offset="1" class="ph7rypboq"/></radialGradient><radialGradient id="it0zbCc" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -48.73 48.601)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iF77ree" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 21.921)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iPT1efd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.827)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iqM9XDb" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.243 15.038)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="i2rnVye" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.87 10.354)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iQdwSUb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.015)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iUOn9Bc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.046)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="iZPWVeb" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.517)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iv7fJ5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.296)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="iN3chWb" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.335 10.718)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="i6TS28c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 20.859)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="iRnqP1b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.827)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="ioy69Uc" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.046)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="v0g3nqbgo"/><stop offset="1" class="mcj2tdbkt"/></radialGradient><radialGradient id="iu7ttPd" cx="0" cy="0" r="1" gradientTransform="rotate(-75.213 13.74 -7.56)scale(.49693 .55747)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="g3_fttbxk"/><stop offset="1" class="brpcnabhe"/></radialGradient><radialGradient id="iYdx4oi" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.39)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="iBz38kc" width="4.17" height="4.439" x="14.414" y="5.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.615686 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="iOZ4xHc" width=".763" height=".367" x="17.245" y="6.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.243137 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="iyXpXOd" width="5.17" height="3.72" x="13.955" y="4.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.564706 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="ii7BUkd" width="6.377" height="6.141" x="9.574" y="8.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.447059 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.447059 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23063" result="effect2_innerShadow_3987_23063"/></filter><filter id="i8gcTbe" width="27.983" height="6.037" x="2.059" y="20.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="ilWJ4Dd" width="24.059" height="2.191" x="3.886" y="15.422" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="iypfZze" width="1.234" height=".876" x="19.618" y="12.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="iY8x9Ee" width="6.802" height="6.803" x="8.337" y="19.16" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="icdkcCc" width="27.983" height="6.037" x="1.959" y="23.921" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="iwSVkXd" width="6.678" height="4.108" x="14.785" y="10.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.607843 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><filter id="iLZ4gHG" width="3.882" height="3.705" x="12.803" y="9.146" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.392157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23063"/></filter><linearGradient id="ipbpqNd" x1="25.051" x2="7.801" y1="18.765" y2="24.14" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iVF7qJc" x1="27.145" x2="26.441" y1="20.327" y2="20.327" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="i50FZvc" x1="16.015" x2="16.395" y1="15.171" y2="18.702" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="iiy3e4b" x1="17.168" x2="17.582" y1="16.206" y2="16.601" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="i0Tj1iR" x1="19.52" x2="19.184" y1="15.89" y2="15.538" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="iJL2VKr" x1="18.457" x2="12.738" y1="23.296" y2="33.39" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="igmUtie" x1="18.02" x2="18.02" y1="29.859" y2="29.577" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-rowing-boat" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.adpffqb5u {
  d: path("M15.931 9.561a4.2 4.2 0 0 1-1.203-.91c-.38-.408-.386-1-.172-1.514l.327-.786a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.182.576.644.369 1.476c-.229 1.08-.501 1.743-.749 2.226c-.177.345-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.bfsiezbmr {
  d: path("M15.919 6.47a.625.625 0 0 0-.373 1.175z");
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.brpcnabhe {
  stop-color: var(--svg-color--aa8d86, #AA8D86);
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

.ebzms6b8q {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.422px;
  rx: 1.095px;
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.ez8jvgb-h {
  stop-color: var(--svg-color--e7a740, #E7A740);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fddv1-bhi {
  stop-color: var(--svg-color--e8af34, #E8AF34);
}

.fqhmacygq {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.98 8.365a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3_fttbxk {
  stop-color: var(--svg-color--81504c, #81504C);
}

.gg_m2zbqv {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.677c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.278l-.003.01c-.015.059.01.118.066.133z");
}

.hdjy9rbia {
  d: path("M13.004 10.968c.6.719 1.333 1.555 1.625 1.883l1.656-1.485c-.33-.395-1.117-1.303-1.617-1.765c-.625-.578-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

.hj5q0lb4p {
  stop-color: var(--svg-color--ffd43f, #FFD43F);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ii_74fbyn {
  d: path("M11.366 20.222a1.917 1.917 0 0 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.711z");
}

.imybosvwl {
  d: path("M21.334 12.173a.59.59 0 1 1 .829.84l-8.439 8.331a.59.59 0 0 1-.829-.84z");
}

.it6t3x2fl {
  stop-color: var(--svg-color--ffb02d, #FFB02D);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jge5r9byj {
  d: path("M3.504 24.343c-.775-.425-1.254-.422-1.445-.422v5.938H29.94V23.92c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.kkmkysy7w {
  fill: var(--svg-color--bf6559, #BF6559);
  fill-rule: evenodd;
  d: path("M17.866 6.844a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 0 1-.083.182");
}

.lov826b0t {
  stop-color: var(--svg-color--9d7d15, #9D7D15);
}

.lvejfg9su {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 12.958px;
  fill: var(--svg-color--f4c03b, #F4C03B);
  rx: 0.318px;
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

.mf6h7sjsc {
  d: path("M18.232 7.956c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.14.515-.031c.098-.121.079-.301-.023-.485");
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mx8nfvb1t {
  stop-color: var(--svg-color--ffcc3f, #FFCC3F);
}

.mxpb4bwvu {
  stop-color: var(--svg-color--ffb72e, #FFB72E);
}

.n61r1nbbs {
  d: path("M14.713 7.6h1.744v2h-1.744z");
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.o6qeis12c {
  d: path("m5.232 16.88l21.725-.021v6.25L8.949 22.99z");
}

.p0r8r5bwk {
  stop-color: var(--svg-color--ffad2d, #FFAD2D);
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

.ppjz_ab6v {
  d: path("M17.72 7.698c.02-.037.038-.064.051-.113c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.123z");
}

.q8kvbpx8t {
  stop-color: var(--svg-color--ffd13f, #FFD13F);
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qs775uzcx {
  d: path("M3.504 20.843c-.775-.425-1.254-.422-1.445-.422v5.938H29.94V20.42c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.r-v52zbsa {
  d: path("M9.598 13.624c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
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

.v0g3nqbgo {
  stop-color: var(--svg-color--579ff0, #579FF0);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v2y4mzboj {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.305c.016-.036.07-.048.119-.026s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.107");
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.wjlwbzb_i {
  fill: var(--svg-color--338ae5, #338AE5);
  d: path("M11.168 10.468c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.wntbizbps {
  d: path("M13.992 7.152c-.16-1.207.231-2.071.46-2.418a.98.98 0 0 1 .867-.515c.324-.004.493.168.75.121c.103-.019.474-.156.77.027c.246.153.445.235.605.235c.227 0 .557-.044.797.3c.25.36.543.332.695.575s.137.773-.277.968c-.414.196-1.313-.21-1.641-.343s-.55-.075-.752.246c-.163.256-.462.311-.592.316c-.093.193-.307.696-.61.992c-.322.317-1 .035-1.072-.504");
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

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xuvoz5f8s {
  d: path("M11.168 10.468c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.y-c17bb3v {
  d: path("M17.641 7.676q.045-.05.061-.11c.027-.098-.019-.206-.097-.227c-.08-.02-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.ynstgccdl {
  stop-color: var(--svg-color--275dc4, #275DC4);
}

.z0ce-5bzk {
  stop-color: var(--svg-color--ffb92f, #FFB92F);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zfmr3z7nq {
  fill: var(--svg-color--ffd839, #FFD839);
  d: path("M16.504 13.679c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>

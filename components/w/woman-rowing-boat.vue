<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iUCGcMe)" transform="rotate(39.16 14.148 7.616)" class="ufqve8b1e"/><path fill="url(#inNQO2d)" class="s3wuhsqxq"/><g filter="url(#i0wjCWd)"><path fill="url(#ifk4vMD)" class="k25gqzqdw"/></g><path clip-rule="evenodd" class="m2ybf1mnk"/><g filter="url(#iMtHwIF)"><path clip-rule="evenodd" class="iflmiffum"/></g><g filter="url(#iGmm4od)"><path class="jenaziy7u"/><path fill="url(#ikFtgGH)" class="st9v9pbat"/></g><path fill="url(#iQCMync)" class="fmqspf0qw"/><path fill="url(#iffIV3d)" class="r_d6-3bqg"/><path fill="url(#iJKxxFK)" class="r_d6-3bqg"/><path fill="url(#iWhavpe)" class="r_d6-3bqg"/><path fill="url(#iNKK6Wb)" class="r_d6-3bqg"/><g filter="url(#iAlMzqe)"><path fill="url(#i6ClXdk)" class="d1ojori6q"/><path fill="url(#iB5Mxue)" class="d1ojori6q"/><path fill="url(#iPxcwbb)" class="d1ojori6q"/></g><g filter="url(#iB982je)"><rect fill="url(#iYMO7Qd)" class="j88kh540q"/><rect fill="url(#iTXllHc)" class="j88kh540q"/><rect fill="url(#ibN4jMc)" class="j88kh540q"/><rect fill="url(#igDW4Gp)" class="j88kh540q"/></g><g filter="url(#iW3tsib)"><rect transform="rotate(-21.787 18.958 12.974)" class="tl49duflx"/></g><path fill="url(#ixrg9ob)" class="mbwbaymdc"/><path fill="url(#ixK7Vrd)" class="mbwbaymdc"/><path fill="url(#ipvf7zd)" class="mbwbaymdc"/><g filter="url(#iRQvrYb)"><path fill="url(#iriTLEc)" class="jb40t6s7p"/></g><g filter="url(#i6vAgZc)"><path fill="url(#imgsjwb)" class="w71rxkbqx"/><path fill="url(#ijLmukd)" class="w71rxkbqx"/><path fill="url(#ipDlCte)" class="w71rxkbqx"/></g><g filter="url(#irJozTb)"><path class="wky7d2biz"/></g><g filter="url(#iQSDobe)"><path fill="url(#iqCzO9d)" class="f_i7j_oqf"/></g><path fill="url(#ieAO68b)" class="rxxzr37ln"/><path class="k8ca85lwr"/><path fill="url(#iTXKiOb)" class="w6k4e-k0p"/><path fill="url(#iNxOZdd)" class="qpna1fbpe"/><path class="t7pqvc07z"/><g filter="url(#i59zs9b)"><path fill="url(#iY5B6vb)" class="t4__6-b7s"/></g><defs><radialGradient id="iUCGcMe" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.064 9.423)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="b_ep1bj6x"/><stop offset="1" class="pqw-311jn"/></radialGradient><radialGradient id="inNQO2d" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.011 10.278)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="q8kvbpx8t"/><stop offset="1" class="ez8jvgb-h"/></radialGradient><radialGradient id="ifk4vMD" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 7.897 5.189)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="hj5q0lb4p"/><stop offset="1" class="p0r8r5bwk"/></radialGradient><radialGradient id="ikFtgGH" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.27 14.811)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ik1b347lr"/><stop offset="1" class="fyswmcz3l"/></radialGradient><radialGradient id="iQCMync" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.074 46.48)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iWhavpe" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 12.58 21.937)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iNKK6Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 10.767 21.844)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="i6ClXdk" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 6.957 14.924)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iB5Mxue" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.59 10.484)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iPxcwbb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 30.986 23.031)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iTXllHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 26.986 16.062)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="ibN4jMc" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 3.705 16.533)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="igDW4Gp" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.392 16.312)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="ixrg9ob" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.049 10.61)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iriTLEc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.075 20.875)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="ijLmukd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 29.61 28.844)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iqCzO9d" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 14.61 10.062)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="d8l2uy9_q"/><stop offset="1" class="ml-wi-9ur"/></radialGradient><radialGradient id="ieAO68b" cx="0" cy="0" r="1" gradientTransform="matrix(-.36061 .26664 -.28066 -.37957 16.892 7.183)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iTXKiOb" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 16.978 7.672)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="g3_fttbxk"/><stop offset="1" class="brpcnabhe"/></radialGradient><radialGradient id="iNxOZdd" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 16.925 7.406)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iY5B6vb" cx="0" cy="0" r="1" gradientTransform="rotate(163.726 8.607 4.23)scale(5.51114 6.88417)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="lelniimio"/><stop offset="1" class="lfhr9hbju"/></radialGradient><filter id="i0wjCWd" width="4.364" height="4.439" x="13.655" y="5.367" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.486275 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iMtHwIF" width=".763" height=".367" x="16.68" y="6.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.243137 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iGmm4od" width="6.377" height="6.141" x="9.009" y="8.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.321569 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iAlMzqe" width="27.983" height="6.037" x="1.494" y="20.437" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iB982je" width="24.059" height="2.191" x="3.321" y="15.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iW3tsib" width="1.234" height=".876" x="19.053" y="12.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iRQvrYb" width="6.802" height="6.803" x="7.772" y="19.176" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="i6vAgZc" width="27.983" height="6.037" x="1.394" y="23.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="irJozTb" width="6.678" height="4.108" x="14.22" y="10.762" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.607843 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="iQSDobe" width="3.882" height="3.705" x="12.238" y="9.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.243137 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><filter id="i59zs9b" width="6.317" height="5.313" x="12.341" y="3.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.490196 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23062"/></filter><linearGradient id="iffIV3d" x1="24.486" x2="7.236" y1="18.781" y2="24.156" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iJKxxFK" x1="26.58" x2="25.877" y1="20.344" y2="20.344" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iYMO7Qd" x1="15.45" x2="15.83" y1="15.187" y2="18.719" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="ixK7Vrd" x1="16.603" x2="17.017" y1="16.223" y2="16.617" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="ipvf7zd" x1="18.955" x2="18.619" y1="15.906" y2="15.555" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="imgsjwb" x1="17.892" x2="12.173" y1="23.312" y2="33.406" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ipDlCte" x1="17.455" x2="17.455" y1="29.875" y2="29.594" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-rowing-boat" /></template>
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

.b_ep1bj6x {
  stop-color: var(--svg-color--98711c, #98711C);
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

.brpcnabhe {
  stop-color: var(--svg-color--aa8d86, #AA8D86);
}

.d1ojori6q {
  d: path("M2.939 20.86c-.775-.426-1.254-.423-1.445-.423v5.938h27.883v-5.938c-1.563 0-2.215 1.157-3.532 1.157c-1.316 0-2.187-1.157-3.547-1.157c-1.117 0-2.242 1.157-3.507 1.157c-.973 0-2.204-1.157-3.391-1.157c-1.258 0-2.262 1.157-3.399 1.157c-.558 0-.835-.102-1.539-.438c-.703-.336-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.204-2-.735");
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.d8l2uy9_q {
  stop-color: var(--svg-color--9178d3, #9178D3);
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

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.ez8jvgb-h {
  stop-color: var(--svg-color--e7a740, #E7A740);
}

.f_i7j_oqf {
  d: path("M12.439 10.984c.6.719 1.333 1.555 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.303-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.688-.195 1.367");
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fmqspf0qw {
  d: path("M9.033 13.64c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyswmcz3l {
  stop-color: var(--svg-color--57399f, #57399F);
  stop-opacity: 0;
}

.g3_fttbxk {
  stop-color: var(--svg-color--81504c, #81504C);
}

.hj5q0lb4p {
  stop-color: var(--svg-color--ffd43f, #FFD43F);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.iflmiffum {
  fill: var(--svg-color--bf6559, #BF6559);
  fill-rule: evenodd;
  d: path("M17.301 6.86a.72.72 0 0 0-.488-.027a.1.1 0 0 1-.066-.19a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ik1b347lr {
  stop-color: var(--svg-color--57399f, #57399F);
}

.j88kh540q {
  width: 23.859px;
  height: 2.191px;
  x: 3.521px;
  y: 15.438px;
  rx: 1.095px;
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jb40t6s7p {
  d: path("M10.801 20.238a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.71z");
}

.jenaziy7u {
  fill: var(--svg-color--7355bd, #7355BD);
  d: path("M10.603 10.484c-1.006 1.232-1.414 2.668-1.594 3.274l3.992 1.25c.126-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.255-1.194-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k25gqzqdw {
  d: path("M15.366 9.577c-.914-.453-1.535-1.234-1.71-1.617l.662-1.592a1.2 1.2 0 0 1 1.034-.738l1.657-.11c.128-.008.262-.003.371.066c.288.183.576.645.369 1.476c-.229 1.08-.5 1.744-.749 2.226c-.177.345-.533.572-.916.506a3 3 0 0 1-.718-.217");
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.k8ca85lwr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.08 7.694c.048.012.099-.027.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.051-.434.03-.5.277l-.002.01c-.016.059.008.118.065.133z");
}

.lelniimio {
  stop-color: var(--svg-color--ffce38, #FFCE38);
}

.lfhr9hbju {
  stop-color: var(--svg-color--ffa738, #FFA738);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m2ybf1mnk {
  fill: var(--svg-color--87004d, #87004D);
  fill-rule: evenodd;
  d: path("M16.415 8.381a.1.1 0 0 1 .132.05a.72.72 0 0 0 .339.325a.1.1 0 1 1-.079.183a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mbwbaymdc {
  d: path("M20.77 12.19a.59.59 0 0 1 .828.839l-8.439 8.331a.59.59 0 1 1-.829-.839z");
}

.ml-wi-9ur {
  stop-color: var(--svg-color--7151be, #7151BE);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.p0r8r5bwk {
  stop-color: var(--svg-color--ffad2d, #FFAD2D);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.pqw-311jn {
  stop-color: var(--svg-color--b97f21, #B97F21);
}

.q8kvbpx8t {
  stop-color: var(--svg-color--ffd13f, #FFD13F);
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qpna1fbpe {
  d: path("M17.076 7.693a.3.3 0 0 0 .061-.11c.027-.1-.018-.206-.097-.227s-.17.039-.198.147a.3.3 0 0 0-.002.126z");
}

.r_d6-3bqg {
  d: path("m4.667 16.896l21.725-.021v6.25l-18.008-.117z");
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.rxxzr37ln {
  d: path("m16.349 7.392l.116.062l.57-.29c-.28-.16-.543-.126-.722.026c-.068.057-.042.16.036.201");
}

.s3wuhsqxq {
  d: path("M17.667 7.973c-.081-.147-.066-.412-.047-.504l-.445 1.02c.14.073.378.138.515-.032c.098-.121.079-.3-.023-.484");
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.st9v9pbat {
  d: path("M10.603 10.484c-1.006 1.232-1.414 2.668-1.594 3.274l3.992 1.25c.126-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.255-1.194-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.t4__6-b7s {
  d: path("M13.034 6.696c.333-.227.419-.441.516-1.094c.22-1.094.542-1.306.969-1.547c.449-.254 1.195-.187 1.703.196c.558.42.668.34 1.348.363c.722.023.972.496.988.91c.015.414-.206.98-.934 1.031c-.834.059-.875-.687-1.574-.53c-.596.132-.727 1.315-.976 1.796c-.159.305-.3 1.013-1.165 1.21c-.921.212-1.68-.562-1.554-1.327c.1-.613.382-.805.68-1.008");
}

.t7pqvc07z {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.98 7.322c.017-.037.07-.049.119-.027s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.106");
}

.tl49duflx {
  width: 1.28px;
  height: 0.637px;
  x: 18.958px;
  y: 12.974px;
  fill: var(--svg-color--f4c03b, #F4C03B);
  rx: 0.318px;
}

.ufqve8b1e {
  d: path("M14.148 7.616h1.744v2h-1.744z");
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.w6k4e-k0p {
  d: path("M17.155 7.714c.02-.037.038-.063.051-.113c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.6.6 0 0 0-.012.123z");
}

.w71rxkbqx {
  d: path("M2.939 24.36c-.775-.426-1.254-.423-1.445-.423v5.938h27.883v-5.938c-1.563 0-2.215 1.157-3.532 1.157c-1.316 0-2.187-1.157-3.547-1.157c-1.117 0-2.242 1.157-3.507 1.157c-.973 0-2.204-1.157-3.391-1.157c-1.258 0-2.262 1.157-3.399 1.157c-.558 0-.835-.102-1.539-.438c-.703-.336-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.204-2-.735");
}

.wky7d2biz {
  fill: var(--svg-color--ffd839, #FFD839);
  d: path("M15.939 13.695c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.253.225-.675.336-1.011.203c-.336-.132-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
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

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>

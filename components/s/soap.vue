<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i3hDpke)" class="tkykgrbtx"/><circle fill="url(#i7xetpu)" class="tkykgrbtx"/><g filter="url(#iZ3onst)"><circle fill="url(#ioY5hfd)" class="cea_y0b2b"/><circle fill="url(#iUdFKoc)" class="cea_y0b2b"/></g><g filter="url(#inarG9c)"><path fill="url(#iZSgGLH)" class="pzuc5dbgs"/><path fill="url(#iqBdKSv)" class="pzuc5dbgs"/><path fill="url(#iWLQUOe)" class="pzuc5dbgs"/><path fill="url(#iihghNb)" class="pzuc5dbgs"/><path fill="url(#ioynyze)" class="pzuc5dbgs"/><path fill="url(#iOFtjsb)" class="pzuc5dbgs"/><path fill="url(#ixMl7tc)" class="pzuc5dbgs"/></g><g filter="url(#iKsj2me)"><rect fill="url(#iHcd0et)" transform="rotate(45 17.836 4.513)" class="ep2_a14us"/><rect fill="url(#iZsWUec)" transform="rotate(45 17.836 4.513)" class="ep2_a14us"/><rect stroke="url(#iggCndb)" transform="rotate(45 17.836 4.336)" class="jnhmwab3a"/></g><g filter="url(#iM6xUMc)"><circle fill="url(#iGT4phb)" class="qwyc8ua0d"/><circle fill="url(#imuy5Nd)" class="qwyc8ua0d"/><circle fill="url(#i47at4N)" class="qwyc8ua0d"/></g><g filter="url(#ieBDitW)"><path fill="url(#i1gAykE)" class="gx9ivmbxa"/><path fill="url(#iWZ4UGM)" class="gx9ivmbxa"/></g><circle fill="url(#il7fo3b)" class="o6n6_pqtf"/><circle fill="url(#i8rYjwe)" class="o6n6_pqtf"/><g filter="url(#iHXhvgb)"><circle fill="url(#ipU6EFd)" class="arxdm5mxl"/><circle fill="url(#i6Ds0qP)" class="arxdm5mxl"/><circle fill="url(#iSxXkNb)" class="arxdm5mxl"/></g><circle fill="url(#iTu1SQb)" class="arxdm5mxl"/><defs><radialGradient id="i3hDpke" cx="0" cy="0" r="1" gradientTransform="rotate(-8.079 73.231 -32.798)scale(4.21168)" gradientUnits="userSpaceOnUse"><stop class="x2zsoqj0p"/><stop offset="1" class="qdfn42bow"/></radialGradient><radialGradient id="i7xetpu" cx="0" cy="0" r="1" gradientTransform="rotate(180 4.238 4.983)scale(3.13998)" gradientUnits="userSpaceOnUse"><stop offset=".529" class="r1ey1dmrg"/><stop offset="1" class="cp_i2acku"/></radialGradient><radialGradient id="ioY5hfd" cx="0" cy="0" r="1" gradientTransform="rotate(168.14 2.09 3.164)scale(1.92063 1.81766)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="pjylx3kxc"/><stop offset=".911" class="aho7l7bck"/></radialGradient><radialGradient id="iUdFKoc" cx="0" cy="0" r="1" gradientTransform="rotate(-100.366 4.982 1.6)scale(1.86971)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="si7ywuxlx"/><stop offset="1" class="u5phg13rl"/></radialGradient><radialGradient id="iqBdKSv" cx="0" cy="0" r="1" gradientTransform="rotate(-111.029 17.734 .865)scale(18.5947 25.5852)" gradientUnits="userSpaceOnUse"><stop offset=".713" class="q_-jxfy3h"/><stop offset=".965" class="glyv33b9i"/></radialGradient><radialGradient id="iWLQUOe" cx="0" cy="0" r="1" gradientTransform="matrix(7.68747 -7.99997 5.66568 5.44437 6.367 12.872)" gradientUnits="userSpaceOnUse"><stop class="upgomh40v"/><stop offset="1" class="um24txzlq"/></radialGradient><radialGradient id="iihghNb" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 -2.639 9.552)scale(2.57391 1.92148)" gradientUnits="userSpaceOnUse"><stop class="leteeabqs"/><stop offset="1" class="gkkc-3b7c"/></radialGradient><radialGradient id="ioynyze" cx="0" cy="0" r="1" gradientTransform="matrix(-6 2.37497 -2.52498 -6.379 21.68 24.31)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="n_7dskevp"/><stop offset="1" class="qut_p17tv"/></radialGradient><radialGradient id="iOFtjsb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.25005 -5.3125 4.91486 -1.15648 27.992 19.872)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="cg24i8daj"/><stop offset="1" class="sqe4gvbiq"/></radialGradient><radialGradient id="ixMl7tc" cx="0" cy="0" r="1" gradientTransform="matrix(4.67724 -.375 .51136 6.37804 25.242 11.31)" gradientUnits="userSpaceOnUse"><stop class="v381j8bth"/><stop offset="1" class="l8-sv9bfm"/></radialGradient><radialGradient id="iGT4phb" cx="0" cy="0" r="1" gradientTransform="rotate(171.772 2.762 6.897)scale(4.41078 4.17429)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="pjylx3kxc"/><stop offset="1" class="dnnzw8b8z"/></radialGradient><radialGradient id="imuy5Nd" cx="0" cy="0" r="1" gradientTransform="matrix(3.21875 -1.52824 2.19502 4.62311 2.117 15.72)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="tdhgvbb1n"/><stop offset="1" class="ir4xwgb2t"/></radialGradient><radialGradient id="i47at4N" cx="0" cy="0" r="1" gradientTransform="rotate(-100.366 9.461 5.266)scale(5.16993)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="si7ywuxlx"/><stop offset="1" class="u5phg13rl"/></radialGradient><radialGradient id="iWZ4UGM" cx="0" cy="0" r="1" gradientTransform="matrix(-2.55893 2.9143 -2.22072 -1.94992 22.058 20.58)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="we9hvtbme"/><stop offset="1" class="q-pav2bho"/></radialGradient><radialGradient id="il7fo3b" cx="0" cy="0" r="1" gradientTransform="rotate(-99.462 22.552 4.98)scale(3.45895)" gradientUnits="userSpaceOnUse"><stop class="aounygz9b"/><stop offset="1" class="uxqbydbhh"/></radialGradient><radialGradient id="i8rYjwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.74147 2.13244 -2.9367 -2.39828 23.729 25.484)" gradientUnits="userSpaceOnUse"><stop offset=".381" class="gxue9wb4r"/><stop offset="1" class="wwid0razy"/></radialGradient><radialGradient id="ipU6EFd" cx="0" cy="0" r="1" gradientTransform="rotate(167.646 13.048 12.11)scale(8.01567 7.5859)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="pjylx3kxc"/><stop offset="1" class="dnnzw8b8z"/></radialGradient><radialGradient id="i6Ds0qP" cx="0" cy="0" r="1" gradientTransform="matrix(4.00097 -2.26155 3.24828 5.74662 20.555 25.423)" gradientUnits="userSpaceOnUse"><stop offset=".182" class="tdhgvbb1n"/><stop offset="1" class="ir4xwgb2t"/></radialGradient><radialGradient id="iSxXkNb" cx="0" cy="0" r="1" gradientTransform="rotate(-100.366 23.565 1.655)scale(7.51647)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="si7ywuxlx"/><stop offset="1" class="u5phg13rl"/></radialGradient><radialGradient id="iTu1SQb" cx="0" cy="0" r="1" gradientTransform="rotate(98.499 4.867 21.04)scale(7.84952 9.63202)" gradientUnits="userSpaceOnUse"><stop offset=".681" class="p-8fdubqr"/><stop offset="1" class="rxzyn-bwy"/></radialGradient><filter id="iZ3onst" width="2.428" height="2.428" x="2.906" y="4.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.737255 0 0 0 0 0.92549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26261"/></filter><filter id="inarG9c" width="28.139" height="27.839" x="2.081" y="2.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.94902 0 0 0 0 0.564706 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26261"/></filter><filter id="iKsj2me" width="22.749" height="22.749" x="4.625" y="4.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26261" stdDeviation=".375"/></filter><filter id="iM6xUMc" width="6.537" height="6.537" x="2.117" y="10.335" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.843137 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26261"/></filter><filter id="ieBDitW" width="12.487" height="21.989" x="14.637" y="5.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_26261" stdDeviation=".375"/></filter><filter id="iHXhvgb" width="9.759" height="9.459" x="20.555" y="17.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.54902 0 0 0 0 0.894118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26261"/></filter><linearGradient id="iZSgGLH" x1="26.867" x2="7.43" y1="7.81" y2="25.685" gradientUnits="userSpaceOnUse"><stop class="yqlyu2exe"/><stop offset="1" class="s-l5t7sve"/></linearGradient><linearGradient id="iHcd0et" x1="24.752" x2="24.752" y1="4.513" y2="23.096" gradientUnits="userSpaceOnUse"><stop class="p55j0r13v"/><stop offset="1" class="kqbte9bfx"/></linearGradient><linearGradient id="iZsWUec" x1="25.57" x2="25.526" y1="23.803" y2="19.517" gradientUnits="userSpaceOnUse"><stop offset=".178" class="c8akjcn_n"/><stop offset="1" class="bjmp4wesm"/></linearGradient><linearGradient id="iggCndb" x1="15.947" x2="20.269" y1="13.324" y2="13.512" gradientUnits="userSpaceOnUse"><stop offset=".493" class="s2d_0j1gv"/><stop offset="1" class="zveaf9b6p"/></linearGradient><linearGradient id="i1gAykE" x1="15.387" x2="24.414" y1="23.81" y2="15.497" gradientUnits="userSpaceOnUse"><stop class="a_49j0bav"/><stop offset="1" class="d1mfah5bo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:soap" /></template>
<style>
.a_49j0bav {
  stop-color: var(--svg-color--f068cb, #F068CB);
}

.aho7l7bck {
  stop-color: var(--svg-color--dbcbea, #DBCBEA);
}

.aounygz9b {
  stop-color: var(--svg-color--eda5ff, #EDA5FF);
}

.arxdm5mxl {
  cx: 25.234px;
  cy: 22.419px;
  r: 4.68px;
}

.bjmp4wesm {
  stop-color: var(--svg-color--ff83e6, #FF83E6);
  stop-opacity: 0;
}

.c8akjcn_n {
  stop-color: var(--svg-color--ff83e6, #FF83E6);
}

.cea_y0b2b {
  cx: 4.07px;
  cy: 6.114px;
  r: 1.164px;
}

.cg24i8daj {
  stop-color: var(--svg-color--e588a9, #E588A9);
}

.cp_i2acku {
  stop-color: var(--svg-color--e4dfe8, #E4DFE8);
}

.d1mfah5bo {
  stop-color: var(--svg-color--f068cb, #F068CB);
  stop-opacity: 0;
}

.dnnzw8b8z {
  stop-color: var(--svg-color--ecaeff, #ECAEFF);
}

.ep2_a14us {
  width: 13.833px;
  height: 19.026px;
  x: 17.836px;
  y: 4.513px;
  rx: 3px;
}

.ft5dv1b6b {
  fill: none;
}

.gkkc-3b7c {
  stop-color: var(--svg-color--e551c0, #E551C0);
  stop-opacity: 0;
}

.glyv33b9i {
  stop-color: var(--svg-color--e1959a, #E1959A);
}

.gx9ivmbxa {
  d: path("m15.388 26.245l1.45-20.32a3 3 0 0 1 3.12.71l5.538 5.538a3 3 0 0 1 0 4.242l-9.21 9.21a3 3 0 0 1-.899.62");
}

.gxue9wb4r {
  stop-color: var(--svg-color--d89aff, #D89AFF);
}

.ir4xwgb2t {
  stop-color: var(--svg-color--dbb6ff, #DBB6FF);
  stop-opacity: 0;
}

.jnhmwab3a {
  width: 14.083px;
  height: 19.276px;
  x: 17.836px;
  y: 4.336px;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  rx: 3.125px;
}

.kqbte9bfx {
  stop-color: var(--svg-color--ff7be6, #FF7BE6);
}

.l8-sv9bfm {
  stop-color: var(--svg-color--ffa7c0, #FFA7C0);
  stop-opacity: 0;
}

.leteeabqs {
  stop-color: var(--svg-color--e551c0, #E551C0);
}

.n_7dskevp {
  stop-color: var(--svg-color--d24bb4, #D24BB4);
}

.o6n6_pqtf {
  cx: 21.648px;
  cy: 26.544px;
  r: 2.734px;
}

.p-8fdubqr {
  stop-color: var(--svg-color--f3b7ff, #F3B7FF);
  stop-opacity: 0;
}

.p55j0r13v {
  stop-color: var(--svg-color--ee7bbe, #EE7BBE);
}

.pjylx3kxc {
  stop-color: var(--svg-color--ffedff, #FFEDFF);
}

.pzuc5dbgs {
  d: path("M13.545 4.085a6.4 6.4 0 0 1 9.05 0l5.45 5.45a6.4 6.4 0 0 1 0 9.05l-9.59 9.59a6.4 6.4 0 0 1-9.05 0l-5.45-5.45a6.4 6.4 0 0 1 0-9.05z");
}

.q_-jxfy3h {
  stop-color: var(--svg-color--e082a1, #E082A1);
  stop-opacity: 0;
}

.q-pav2bho {
  stop-color: var(--svg-color--d35f9e, #D35F9E);
  stop-opacity: 0;
}

.qdfn42bow {
  stop-color: var(--svg-color--c8c1c9, #C8C1C9);
}

.qut_p17tv {
  stop-color: var(--svg-color--d24bb4, #D24BB4);
  stop-opacity: 0;
}

.qwyc8ua0d {
  cx: 5.336px;
  cy: 13.653px;
  r: 3.219px;
}

.r1ey1dmrg {
  stop-color: var(--svg-color--cec5d1, #CEC5D1);
  stop-opacity: 0;
}

.rxzyn-bwy {
  stop-color: var(--svg-color--e697ff, #E697FF);
}

.s-l5t7sve {
  stop-color: var(--svg-color--f756e5, #F756E5);
}

.s2d_0j1gv {
  stop-color: var(--svg-color--f89bb9, #F89BB9);
}

.si7ywuxlx {
  stop-color: var(--svg-color--dad4e0, #DAD4E0);
  stop-opacity: 0;
}

.sqe4gvbiq {
  stop-color: var(--svg-color--e588a9, #E588A9);
  stop-opacity: 0;
}

.tdhgvbb1n {
  stop-color: var(--svg-color--dbb6ff, #DBB6FF);
}

.tkykgrbtx {
  cx: 7.555px;
  cy: 9.966px;
  r: 2.219px;
}

.u5phg13rl {
  stop-color: var(--svg-color--dad4e0, #DAD4E0);
}

.um24txzlq {
  stop-color: var(--svg-color--e775ab, #E775AB);
  stop-opacity: 0;
}

.upgomh40v {
  stop-color: var(--svg-color--e775ab, #E775AB);
}

.uxqbydbhh {
  stop-color: var(--svg-color--c28cdd, #C28CDD);
}

.v381j8bth {
  stop-color: var(--svg-color--ffa7c0, #FFA7C0);
}

.we9hvtbme {
  stop-color: var(--svg-color--d35f9e, #D35F9E);
}

.wwid0razy {
  stop-color: var(--svg-color--d89aff, #D89AFF);
  stop-opacity: 0;
}

.x2zsoqj0p {
  stop-color: var(--svg-color--cec4d1, #CEC4D1);
}

.yqlyu2exe {
  stop-color: var(--svg-color--ffabbd, #FFABBD);
}

.zveaf9b6p {
  stop-color: var(--svg-color--f89bb9, #F89BB9);
  stop-opacity: 0;
}

</style>

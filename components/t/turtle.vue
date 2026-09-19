<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="p9g66jb5p"/><circle fill="url(#i154fwB)" class="zbb6qgeii"/><circle fill="url(#iTnDvDd)" class="zbb6qgeii"/><circle fill="url(#iNmJiHZ)" class="zbb6qgeii"/><circle fill="url(#iRSGcAc)" class="zbb6qgeii"/><g filter="url(#i5ae4Yc)"><circle class="nx-2obb5v"/></g><path class="b9xzgeb_r"/><path fill="url(#imdId2q)" class="mlv7pbydj"/><path fill="url(#iyAF3sd)" class="mlv7pbydj"/><path fill="url(#ifp40Nb)" class="mlv7pbydj"/><path fill="url(#iFTrngd)" class="mlv7pbydj"/><path fill="url(#ihuTazc)" class="mlv7pbydj"/><path class="p6pne8cul"/><path fill="url(#iRLPIyd)" class="p3m8cujgb"/><path fill="url(#iGL93bb)" class="p3m8cujgb"/><path fill="url(#iP94vnA)" class="p3m8cujgb"/><path fill="url(#iGlpgDb)" class="p3m8cujgb"/><path fill="url(#iWUlYXc)" class="p3m8cujgb"/><path fill="url(#i6CBQ9b)" class="p57-kjepk"/><path fill="url(#izHPZqb)" class="p57-kjepk"/><path fill="url(#igDma7d)" class="p57-kjepk"/><path fill="url(#iO1JUMe)" class="p57-kjepk"/><g filter="url(#iBxQmNb)"><path fill="url(#i5d1ITc)" class="cpyvzbczy"/><path fill="url(#iGWsG6d)" class="cpyvzbczy"/><path fill="url(#ivB8nwd)" class="cpyvzbczy"/><path fill="url(#iu1N7Vc)" class="cpyvzbczy"/><path fill="url(#iTkA3ie)" class="cpyvzbczy"/></g><path fill="url(#iZ4Gvad)" class="cpyvzbczy"/><path fill="url(#irN9Vtd)" class="cpyvzbczy"/><circle fill="url(#iEXQdhe)" class="oollt3u_x"/><circle fill="url(#iV10i1b)" class="oollt3u_x"/><g filter="url(#iUF1gne)"><path fill="url(#iANs7nd)" clip-rule="evenodd" class="yfveg6bpt"/></g><g filter="url(#iUF1gne)"><path fill="url(#iwU8ngb)" clip-rule="evenodd" class="yfveg6bpt"/></g><g filter="url(#iePSptb)"><path stroke="url(#iRLjmXb)" class="i80dgob3k"/></g><g filter="url(#if4HYWb)"><path stroke="url(#ic1Ub1c)" class="zef2u3byg"/></g><g filter="url(#ijIabSd)"><path stroke="url(#imTkEAb)" class="vto40rb5j"/></g><g filter="url(#i0kB6mb)"><path stroke="url(#io4mqkc)" class="m3ac-szut"/></g><g filter="url(#ilt5Opc)"><path stroke="url(#iGNPKEe)" class="wky_eyrlx"/></g><defs><linearGradient id="i154fwB" x1="3.797" x2="3.797" y1="26.344" y2="23.5" gradientUnits="userSpaceOnUse"><stop class="kzuu0cbid"/><stop offset=".958" class="omyaidklz"/></linearGradient><linearGradient id="iyAF3sd" x1="6.985" x2="6.985" y1="30.344" y2="28.25" gradientUnits="userSpaceOnUse"><stop class="kzuu0cbid"/><stop offset=".958" class="omyaidklz"/></linearGradient><linearGradient id="ifp40Nb" x1="10.328" x2="9.516" y1="26" y2="28.5" gradientUnits="userSpaceOnUse"><stop offset=".119" class="umvtedcst"/><stop offset=".958" class="u9xn10b1h"/></linearGradient><linearGradient id="iFTrngd" x1="8.991" x2="8.991" y1="25.563" y2="30.141" gradientUnits="userSpaceOnUse"><stop offset=".809" class="k6dp66brm"/><stop offset=".979" class="toxv0abqx"/></linearGradient><linearGradient id="ihuTazc" x1="13.448" x2="4.789" y1="27.759" y2="27.759" gradientUnits="userSpaceOnUse"><stop offset=".939" class="jkeixpbox"/><stop offset="1" class="fvoj6ru5y"/></linearGradient><linearGradient id="iGL93bb" x1="21.953" x2="21.953" y1="31" y2="28.813" gradientUnits="userSpaceOnUse"><stop class="kzuu0cbid"/><stop offset=".958" class="omyaidklz"/></linearGradient><linearGradient id="iP94vnA" x1="22.672" x2="23.96" y1="25.938" y2="28.75" gradientUnits="userSpaceOnUse"><stop offset=".119" class="umvtedcst"/><stop offset=".958" class="u9xn10b1h"/></linearGradient><linearGradient id="iGlpgDb" x1="23.96" x2="23.96" y1="25.5" y2="29.938" gradientUnits="userSpaceOnUse"><stop offset=".809" class="k6dp66brm"/><stop offset=".979" class="toxv0abqx"/></linearGradient><linearGradient id="i6CBQ9b" x1="28.828" x2="28.641" y1="24.906" y2="26.719" gradientUnits="userSpaceOnUse"><stop class="bl7nhbx4t"/><stop offset="1" class="l1c34eb5f"/></linearGradient><linearGradient id="izHPZqb" x1="28.953" x2="28.703" y1="24.859" y2="25.172" gradientUnits="userSpaceOnUse"><stop class="l1c34eb5f"/><stop offset="1" class="l0zpzib0h"/></linearGradient><linearGradient id="igDma7d" x1="27.766" x2="27.608" y1="27.813" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="kzuu0cbid"/><stop offset=".958" class="omyaidklz"/></linearGradient><linearGradient id="iO1JUMe" x1="28.393" x2="28.393" y1="23.159" y2="27.141" gradientUnits="userSpaceOnUse"><stop offset=".904" class="k6dp66brm"/><stop offset=".965" class="toxv0abqx"/></linearGradient><linearGradient id="ivB8nwd" x1="16.468" x2="16.468" y1="28" y2="25.25" gradientUnits="userSpaceOnUse"><stop class="o5t2mykck"/><stop offset="1" class="jadi-bgis"/></linearGradient><linearGradient id="iu1N7Vc" x1="30.235" x2="26.297" y1="25.25" y2="25.25" gradientUnits="userSpaceOnUse"><stop class="o5t2mykck"/><stop offset="1" class="jadi-bgis"/></linearGradient><linearGradient id="iZ4Gvad" x1="16.468" x2="16.468" y1="28.063" y2="25.75" gradientUnits="userSpaceOnUse"><stop class="pokjjjq8k"/><stop offset="1" class="paha3oxyi"/></linearGradient><linearGradient id="irN9Vtd" x1="16.468" x2="16.468" y1="27.375" y2="25.25" gradientUnits="userSpaceOnUse"><stop class="o5t2mykck"/><stop offset=".647" class="jadi-bgis"/></linearGradient><linearGradient id="iANs7nd" x1="16.477" x2="16.477" y1="17.563" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="f9975wecv"/><stop offset="1" class="mwwdqcboo"/></linearGradient><linearGradient id="iRLjmXb" x1="22.453" x2="17.672" y1="16.438" y2="18.75" gradientUnits="userSpaceOnUse"><stop class="zavm1vk-u"/><stop offset="1" class="k8en3ypjv"/></linearGradient><linearGradient id="ic1Ub1c" x1="24.844" x2="11.797" y1="21.652" y2="26" gradientUnits="userSpaceOnUse"><stop class="zavm1vk-u"/><stop offset="1" class="k8en3ypjv"/></linearGradient><linearGradient id="imTkEAb" x1="12.817" x2="9.766" y1="18.579" y2="18.744" gradientUnits="userSpaceOnUse"><stop class="zavm1vk-u"/><stop offset="1" class="k8en3ypjv"/></linearGradient><linearGradient id="io4mqkc" x1="10.68" x2="11.573" y1="16.82" y2="18.583" gradientUnits="userSpaceOnUse"><stop class="zavm1vk-u"/><stop offset="1" class="k8en3ypjv"/></linearGradient><linearGradient id="iGNPKEe" x1="7.787" x2="8.681" y1="21.707" y2="23.47" gradientUnits="userSpaceOnUse"><stop class="zavm1vk-u"/><stop offset="1" class="k8en3ypjv"/></linearGradient><radialGradient id="iTnDvDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.9375 -4.36106 0 5.547 23.172)" gradientUnits="userSpaceOnUse"><stop offset=".84" class="k6dp66brm"/><stop offset=".979" class="toxv0abqx"/></radialGradient><radialGradient id="iNmJiHZ" cx="0" cy="0" r="1" gradientTransform="rotate(-108.52 10.982 9.197)scale(3.3451 2.12947)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="vve2mvyzh"/><stop offset="1" class="borv2jn8c"/></radialGradient><radialGradient id="iRSGcAc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.78125 .68751 -.68201 -3.751 5.672 23.766)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="jkeixpbox"/><stop offset="1" class="fvoj6ru5y"/></radialGradient><radialGradient id="imdId2q" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 -1.06248 .6432 -2.53502 14.047 28)" gradientUnits="userSpaceOnUse"><stop class="vve2mvyzh"/><stop offset="1" class="borv2jn8c"/></radialGradient><radialGradient id="iRLPIyd" cx="0" cy="0" r="1" gradientTransform="matrix(3.75 1.0625 -.64321 2.27017 19.297 25.938)" gradientUnits="userSpaceOnUse"><stop class="vve2mvyzh"/><stop offset="1" class="borv2jn8c"/></radialGradient><radialGradient id="iWUlYXc" cx="0" cy="0" r="1" gradientTransform="rotate(154.878 11.092 16.576)scale(7.21361 1.91255)" gradientUnits="userSpaceOnUse"><stop class="t384cac8s"/><stop offset="1" class="qnk6x8b-e"/></radialGradient><radialGradient id="i5d1ITc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.87503 -5.69181 8.00352 -6.855 24.485 19.88)" gradientUnits="userSpaceOnUse"><stop class="vwdbfyaho"/><stop offset="1" class="gpbz9fe1l"/></radialGradient><radialGradient id="iGWsG6d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.125 -12.5459 0 16.468 14.438)" gradientUnits="userSpaceOnUse"><stop class="mp68gybec"/><stop offset="1" class="v3flq7bsu"/></radialGradient><radialGradient id="iTkA3ie" cx="0" cy="0" r="1" gradientTransform="rotate(16.221 -66.942 29.637)scale(5.91201 6.50475)" gradientUnits="userSpaceOnUse"><stop class="sa83macaw"/><stop offset="1" class="inl9e_f5c"/></radialGradient><radialGradient id="iEXQdhe" cx="0" cy="0" r="1" gradientTransform="rotate(-40.601 32.835 5.662)scale(.81349)" gradientUnits="userSpaceOnUse"><stop class="l4svo8b2k"/><stop offset="1" class="lm1i3_b7x"/></radialGradient><radialGradient id="iV10i1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.82812 -.6797 .45178 -.55043 4.852 22.79)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="iizir6bgf"/><stop offset="1" class="v82r8_bfb"/></radialGradient><radialGradient id="iwU8ngb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.75006 13.74994 -29.0569 -10.038 22.672 16.625)" gradientUnits="userSpaceOnUse"><stop class="w3-g2qbwp"/><stop offset="1" class="zspq2xb1b"/></radialGradient><filter id="i5ae4Yc" width="2" height="2" x="3.731" y="21.637" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5496" stdDeviation=".25"/></filter><filter id="iBxQmNb" width="23.089" height="14.346" x="4.998" y="12.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.968627 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5496"/></filter><filter id="iUF1gne" width="18.953" height="9.119" x="7" y="16.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.635294 0 0 0 0 0.47451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5496"/></filter><filter id="iePSptb" width="5.431" height="2.619" x="17.347" y="16.113" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5496" stdDeviation=".125"/></filter><filter id="if4HYWb" width="9.384" height="3.759" x="16.503" y="21.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5496" stdDeviation=".125"/></filter><filter id="ijIabSd" width="2.494" height="4.634" x="10.832" y="18.331" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5496" stdDeviation=".125"/></filter><filter id="i0kB6mb" width="1.775" height="1.509" x="10.199" y="16.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5496" stdDeviation=".125"/></filter><filter id="ilt5Opc" width="1.775" height="1.509" x="7.306" y="21.382" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5496" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:turtle" /></template>
<style>
.b9xzgeb_r {
  fill: var(--svg-color--a7cd4c, #A7CD4C);
  d: path("m4.998 26.98l7.987-.98v2.5a1.5 1.5 0 0 1-1.5 1.5H6.498a1.5 1.5 0 0 1-1.5-1.5z");
}

.bl7nhbx4t {
  stop-color: var(--svg-color--c4ff66, #C4FF66);
}

.borv2jn8c {
  stop-color: var(--svg-color--79b037, #79B037);
  stop-opacity: 0;
}

.cpyvzbczy {
  d: path("M16.39 12.781c-6.42 0-11.345 5.049-11.345 11.469c0 .923-.047 1.813-.047 2.727h22.94V24.22c0-6.42-5.127-11.438-11.547-11.438");
}

.f9975wecv {
  stop-color: var(--svg-color--67bd5b, #67BD5B);
}

.ft5dv1b6b {
  fill: none;
}

.fvoj6ru5y {
  stop-color: var(--svg-color--f0fada, #F0FADA);
}

.gpbz9fe1l {
  stop-color: var(--svg-color--3b9990, #3B9990);
}

.i80dgob3k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.672 18.406c.906.01 3.231-.444 4.781-1.968");
}

.iizir6bgf {
  stop-color: var(--svg-color--736c6c, #736C6C);
  stop-opacity: 0;
}

.inl9e_f5c {
  stop-color: var(--svg-color--7cae9f, #7CAE9F);
  stop-opacity: 0;
}

.jadi-bgis {
  stop-color: var(--svg-color--3d7f92, #3D7F92);
  stop-opacity: 0;
}

.jkeixpbox {
  stop-color: var(--svg-color--f0fada, #F0FADA);
  stop-opacity: 0;
}

.k6dp66brm {
  stop-color: var(--svg-color--d4a6c6, #D4A6C6);
  stop-opacity: 0;
}

.k8en3ypjv {
  stop-color: var(--svg-color--87e27a, #87E27A);
  stop-opacity: 0;
}

.kzuu0cbid {
  stop-color: var(--svg-color--a3a560, #A3A560);
}

.l0zpzib0h {
  stop-color: var(--svg-color--b0e254, #B0E254);
  stop-opacity: 0;
}

.l1c34eb5f {
  stop-color: var(--svg-color--b0e254, #B0E254);
}

.l4svo8b2k {
  stop-color: var(--svg-color--5a2d67, #5A2D67);
}

.lm1i3_b7x {
  stop-color: var(--svg-color--2b2426, #2B2426);
}

.m3ac-szut {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M10.524 16.82c.15.183.64.586 1.125.86");
}

.mlv7pbydj {
  d: path("m4.998 26.98l7.987-.98v2.5a1.5 1.5 0 0 1-1.5 1.5H6.498a1.5 1.5 0 0 1-1.5-1.5z");
}

.mp68gybec {
  stop-color: var(--svg-color--4ca589, #4CA589);
}

.mwwdqcboo {
  stop-color: var(--svg-color--6cb768, #6CB768);
}

.nx-2obb5v {
  cx: 4.731px;
  cy: 22.637px;
  r: 0.5px;
  fill: var(--svg-color--5b841c, #5B841C);
}

.o5t2mykck {
  stop-color: var(--svg-color--3d7f92, #3D7F92);
}

.omyaidklz {
  stop-color: var(--svg-color--a3a560, #A3A560);
  stop-opacity: 0;
}

.oollt3u_x {
  cx: 4.485px;
  cy: 22.438px;
  r: 0.5px;
}

.p3m8cujgb {
  d: path("M19.967 25.938h7.986v2.5a1.5 1.5 0 0 1-1.5 1.5h-4.986a1.5 1.5 0 0 1-1.5-1.5z");
}

.p57-kjepk {
  d: path("M29.64 25.586c-.25-.219-2.152-2.05-2.152-2.05l-.656 3.44h2.36c.25 0 .578-.163.71-.46c.133-.297-.011-.711-.261-.93");
}

.p6pne8cul {
  fill: var(--svg-color--a7cd4c, #A7CD4C);
  d: path("M19.967 25.938h7.986v2.5a1.5 1.5 0 0 1-1.5 1.5h-4.986a1.5 1.5 0 0 1-1.5-1.5z");
}

.p9g66jb5p {
  cx: 5.547px;
  cy: 23.5px;
  r: 3.5px;
  fill: var(--svg-color--a7de50, #A7DE50);
}

.paha3oxyi {
  stop-color: var(--svg-color--3c9a91, #3C9A91);
  stop-opacity: 0;
}

.pokjjjq8k {
  stop-color: var(--svg-color--3c9a91, #3C9A91);
}

.qnk6x8b-e {
  stop-color: var(--svg-color--c0ef52, #C0EF52);
  stop-opacity: 0;
}

.sa83macaw {
  stop-color: var(--svg-color--7cae9f, #7CAE9F);
}

.t384cac8s {
  stop-color: var(--svg-color--c0ef52, #C0EF52);
}

.toxv0abqx {
  stop-color: var(--svg-color--d5a6c6, #D5A6C6);
}

.u9xn10b1h {
  stop-color: var(--svg-color--858d4a, #858D4A);
  stop-opacity: 0;
}

.umvtedcst {
  stop-color: var(--svg-color--858d4a, #858D4A);
}

.v3flq7bsu {
  stop-color: var(--svg-color--4ca589, #4CA589);
  stop-opacity: 0;
}

.v82r8_bfb {
  stop-color: var(--svg-color--736c6c, #736C6C);
}

.vto40rb5j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m13 18.656l-1.844 3.985");
}

.vve2mvyzh {
  stop-color: var(--svg-color--79b037, #79B037);
}

.vwdbfyaho {
  stop-color: var(--svg-color--6fc1ad, #6FC1AD);
}

.w3-g2qbwp {
  stop-color: var(--svg-color--6cd45b, #6CD45B);
}

.wky_eyrlx {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.631 21.707c.151.182.64.586 1.125.86");
}

.yfveg6bpt {
  fill-rule: evenodd;
  d: path("M10.903 16.219a.5.5 0 0 0-.807.59l.404-.293l-.404.294l.002.002l.002.004l.007.008a2 2 0 0 0 .09.11q.09.105.265.27c.235.218.59.5 1.084.779c.318.178.691.355 1.126.512l-2.112 4.387q-.417-.186-.765-.376a8.6 8.6 0 0 1-1.472-.999a5 5 0 0 1-.42-.4l-.017-.02l-.003-.002a.5.5 0 0 0-.767.641l.384-.32l-.384.32v.001l.002.002l.003.003l.009.01a2 2 0 0 0 .135.146c.092.094.227.225.407.38c.362.308.904.713 1.646 1.117c1.486.807 3.758 1.6 6.943 1.6s5.558-.784 7.144-1.577a11.5 11.5 0 0 0 1.785-1.096a8 8 0 0 0 .573-.478l.032-.031l.01-.01l.003-.003l.001-.001l-.356-.352l.357.351a.5.5 0 0 0-.713-.701l-.003.003l-.02.02l-.093.084a7 7 0 0 1-.394.32c-.356.27-.898.634-1.63 1q-.28.14-.596.278l-2.101-4.365c.372-.137.703-.286.992-.436a7 7 0 0 0 1.182-.765a5 5 0 0 0 .399-.367l.007-.008l.003-.003v-.001h.001l-.375-.331l.376.33a.5.5 0 0 0-.75-.662l-.01.01l-.05.052a4 4 0 0 1-.233.204a6 6 0 0 1-1.01.653c-.926.48-2.383.975-4.464.975c-2.08 0-3.453-.495-4.291-.967a4.7 4.7 0 0 1-.895-.64a3 3 0 0 1-.233-.244zm10.524 6.938l-2.133-4.43c-.83.21-1.815.351-2.966.351c-1.041 0-1.93-.115-2.685-.294l-2.149 4.463c1.233.422 2.81.737 4.767.737c2.105 0 3.823-.36 5.166-.827");
}

.zavm1vk-u {
  stop-color: var(--svg-color--87e27a, #87E27A);
}

.zbb6qgeii {
  cx: 5.547px;
  cy: 23.5px;
  r: 3.5px;
}

.zef2u3byg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.828 24.64c3.844-.25 6.204-1.109 8.735-3.109");
}

.zspq2xb1b {
  stop-color: var(--svg-color--6cd45b, #6CD45B);
  stop-opacity: 0;
}

</style>

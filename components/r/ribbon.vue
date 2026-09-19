<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i7GVbCo)" class="feqhtsb6i"/><path fill="url(#iq5hSvt)" class="feqhtsb6i"/><path fill="url(#iq2VB0c)" class="feqhtsb6i"/><path fill="url(#icDzGjb)" class="feqhtsb6i"/><path fill="url(#ieNNQ7b)" class="k-jzqzbvg"/><path fill="url(#iifa4Eb)" class="k-jzqzbvg"/><path fill="url(#itg5yKd)" class="k-jzqzbvg"/><path fill="url(#iZixCGd)" class="k-jzqzbvg"/><path fill="url(#iky9Pje)" class="h-zy0dbsh"/><path fill="url(#iREwmVd)" class="h-zy0dbsh"/><path fill="url(#iNL5OWb)" class="vx07dl_yr"/><path class="ne1-ywb6l"/><path class="bj14qibcc"/><path fill="url(#iEAHq7c)" class="et03uuddm"/><path class="fi1j2tbah"/><path fill="url(#imsDnnj)" class="sjcpqcb9j"/><g filter="url(#iQm2vye)"><path stroke="url(#iji6P4d)" class="gwqr9s7lv"/></g><g filter="url(#iiGiw2c)"><path stroke="url(#i9lNVOc)" class="kia1zs96d"/></g><path stroke="url(#iMXycIe)" class="gwqr9s7lv"/><rect fill="url(#ijPnYYd)" class="w1wx8dn-p"/><rect fill="url(#itzNmwb)" class="w1wx8dn-p"/><rect fill="url(#ikLe8Lb)" class="w1wx8dn-p"/><rect fill="url(#ig1evjb)" class="w1wx8dn-p"/><rect fill="url(#iARyDgb)" class="w1wx8dn-p"/><defs><linearGradient id="i7GVbCo" x1="18.304" x2="21.679" y1="19.702" y2="28.014" gradientUnits="userSpaceOnUse"><stop class="en1_htb6m"/><stop offset="1" class="sit9lobxd"/></linearGradient><linearGradient id="iq5hSvt" x1="22.289" x2="20.351" y1="18.264" y2="21.577" gradientUnits="userSpaceOnUse"><stop offset=".283" class="ilc3whi0p"/><stop offset="1" class="u3h8mkb3k"/></linearGradient><linearGradient id="iq2VB0c" x1="17.378" x2="17.805" y1="22.623" y2="22.478" gradientUnits="userSpaceOnUse"><stop class="hmhtd6bqj"/><stop offset="1" class="mrimfm3ol"/></linearGradient><linearGradient id="icDzGjb" x1="24.993" x2="24.617" y1="23.461" y2="23.598" gradientUnits="userSpaceOnUse"><stop class="y4vrltb0r"/><stop offset="1" class="r0biv5bhk"/></linearGradient><linearGradient id="ieNNQ7b" x1="13.789" x2="10.414" y1="19.702" y2="28.014" gradientUnits="userSpaceOnUse"><stop class="en1_htb6m"/><stop offset="1" class="sit9lobxd"/></linearGradient><linearGradient id="itg5yKd" x1="7.637" x2="8.166" y1="21.97" y2="22.165" gradientUnits="userSpaceOnUse"><stop class="tub-zvbtm"/><stop offset="1" class="xqc8i55uj"/></linearGradient><linearGradient id="iZixCGd" x1="14.244" x2="13.864" y1="24.183" y2="24.034" gradientUnits="userSpaceOnUse"><stop offset=".176" class="mb_ri9bhy"/><stop offset="1" class="cf8lv0bab"/></linearGradient><linearGradient id="iky9Pje" x1="12.914" x2="2" y1="13.889" y2="13.889" gradientUnits="userSpaceOnUse"><stop class="u8kr8j20a"/><stop offset=".497" class="cx8aof56q"/><stop offset="1" class="gqvyn9s-e"/></linearGradient><linearGradient id="iNL5OWb" x1="20.476" x2="29.94" y1="14.014" y2="14.014" gradientUnits="userSpaceOnUse"><stop offset=".092" class="xpk8s-30k"/><stop offset="1" class="zll07hy5k"/></linearGradient><linearGradient id="iji6P4d" x1="19.067" x2="29.813" y1="17.752" y2="17.752" gradientUnits="userSpaceOnUse"><stop class="lpdnf_b0o"/><stop offset="1" class="cc1vfkjxe"/></linearGradient><linearGradient id="i9lNVOc" x1="12.873" x2="2.127" y1="17.752" y2="17.752" gradientUnits="userSpaceOnUse"><stop class="y1xw-vb1l"/><stop offset="1" class="juyx9ybzi"/></linearGradient><linearGradient id="ijPnYYd" x1="16.061" x2="16.061" y1="7.112" y2="20.103" gradientUnits="userSpaceOnUse"><stop class="pzvhaibnx"/><stop offset="1" class="bd0860fgm"/></linearGradient><linearGradient id="itzNmwb" x1="11.733" x2="14.388" y1="12.703" y2="12.889" gradientUnits="userSpaceOnUse"><stop class="cykgc3b5a"/><stop offset="1" class="nwc2uzbna"/></linearGradient><linearGradient id="ig1evjb" x1="19.677" x2="18.675" y1="12.75" y2="12.75" gradientUnits="userSpaceOnUse"><stop class="dj7wml3-g"/><stop offset="1" class="mqj5dyuok"/></linearGradient><linearGradient id="iARyDgb" x1="16.718" x2="16.718" y1="20.577" y2="18.667" gradientUnits="userSpaceOnUse"><stop class="l8tyccbtp"/><stop offset="1" class="jch8xrueq"/></linearGradient><radialGradient id="iifa4Eb" cx="0" cy="0" r="1" gradientTransform="rotate(129.152 3.17 12.242)scale(6.04469 6.91506)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="ilc3whi0p"/><stop offset="1" class="u3h8mkb3k"/></radialGradient><radialGradient id="iREwmVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.9375 3.23171 0 10.476 17.514)" gradientUnits="userSpaceOnUse"><stop class="a41bkrvvj"/><stop offset="1" class="z7hvf9b8c"/></radialGradient><radialGradient id="iEAHq7c" cx="0" cy="0" r="1" gradientTransform="matrix(1.6409 8.51226 -11.6125 2.23853 27.625 12.077)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="a76argnef"/><stop offset="1" class="ptpuywr1j"/></radialGradient><radialGradient id="imsDnnj" cx="0" cy="0" r="1" gradientTransform="rotate(100.911 -2.828 7.82)scale(8.66897 11.8263)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="stlo64bwy"/><stop offset="1" class="ptpuywr1j"/></radialGradient><radialGradient id="iMXycIe" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 -4.50366 5.11314 4.18653 24.601 19.17)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="yx7pws-tr"/><stop offset="1" class="kj60y6b9j"/></radialGradient><radialGradient id="ikLe8Lb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.61266 0 0 -.6523 20.12 17.549)" gradientUnits="userSpaceOnUse"><stop class="u-07f5idp"/><stop offset="1" class="y05g6wbyi"/></radialGradient><filter id="iQm2vye" width="12.006" height="6.785" x="17.688" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.254902 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1233"/></filter><filter id="iiGiw2c" width="12.006" height="6.785" x="2.246" y="14.066" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.25098 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1233"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ribbon" /></template>
<style>
.a41bkrvvj {
  stop-color: var(--svg-color--db3665, #DB3665);
}

.a76argnef {
  stop-color: var(--svg-color--932128, #932128);
}

.bd0860fgm {
  stop-color: var(--svg-color--df1e30, #DF1E30);
}

.bj14qibcc {
  fill: var(--svg-color--c40e49, #C40E49);
  d: path("m23.278 15.352l-4.211 2.069c.657.312 2.932 1.51 4.62 2.25c2.112.927 3.91.4 4.815-.613s.912-3.062-.958-3.996c-1.517-.759-3.146-.291-4.266.29");
}

.cc1vfkjxe {
  stop-color: var(--svg-color--dd1836, #DD1836);
}

.cf8lv0bab {
  stop-color: var(--svg-color--d24162, #D24162);
  stop-opacity: 0;
}

.cx8aof56q {
  stop-color: var(--svg-color--cd2e4e, #CD2E4E);
}

.cykgc3b5a {
  stop-color: var(--svg-color--a2304b, #A2304B);
}

.dj7wml3-g {
  stop-color: var(--svg-color--c11451, #C11451);
}

.en1_htb6m {
  stop-color: var(--svg-color--ba2950, #BA2950);
}

.et03uuddm {
  d: path("m23.278 15.352l-4.211 2.069c.657.312 2.932 1.51 4.62 2.25c2.112.927 3.91.4 4.815-.613s.912-3.062-.958-3.996c-1.517-.759-3.146-.291-4.266.29");
}

.feqhtsb6i {
  d: path("m19.88 29.353l-3.638-9.964l5.922-3.453l4.039 11.094a.75.75 0 0 1-.994.949l-1.839-.77a1 1 0 0 0-1.288.492l-.82 1.718a.75.75 0 0 1-1.382-.066");
}

.fi1j2tbah {
  fill: var(--svg-color--cc0b30, #CC0B30);
  d: path("m8.662 15.352l4.211 2.069c-.657.312-2.932 1.51-4.62 2.25c-2.112.927-3.91.4-4.816-.613c-.904-1.013-.91-3.062.96-3.996c1.516-.759 3.144-.291 4.265.29");
}

.ft5dv1b6b {
  fill: none;
}

.gqvyn9s-e {
  stop-color: var(--svg-color--a1383e, #A1383E);
}

.gwqr9s7lv {
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m18.938 17.691l-.561-.266l.557-.274l4.209-2.066c1.152-.598 2.891-1.114 4.535-.292c2.066 1.033 2.07 3.32 1.048 4.465c-1.005 1.124-2.95 1.658-5.16.688c-1.196-.525-2.704-1.287-3.705-1.794a56 56 0 0 0-.923-.46Z");
}

.h-zy0dbsh {
  d: path("m13.423 9.724l.83-.395l-5.321-2.612c-1.184-.614-3.034-1.177-4.804-.292a3.7 3.7 0 0 0-.907.628c-.527.463-1.216 1.372-1.216 2.968v6.764c-.042.541.179 1.932 1.018 2.709c1.114 1.21 3.184 1.73 5.47.727c1.205-.529 2.74-1.304 3.742-1.811c.404-.204.721-.365.896-.448l1.121-.533l-.83-.407z");
}

.hmhtd6bqj {
  stop-color: var(--svg-color--a80435, #A80435);
}

.ilc3whi0p {
  stop-color: var(--svg-color--980129, #980129);
}

.jch8xrueq {
  stop-color: var(--svg-color--d12951, #D12951);
  stop-opacity: 0;
}

.juyx9ybzi {
  stop-color: var(--svg-color--c81745, #C81745);
}

.k-jzqzbvg {
  d: path("m12.213 29.353l3.638-9.964l-5.922-3.453L5.89 27.03a.75.75 0 0 0 .994.949l1.84-.77a1 1 0 0 1 1.287.492l.821 1.718a.75.75 0 0 0 1.381-.066");
}

.kia1zs96d {
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m13.002 17.691l.56-.266l-.557-.274l-4.208-2.066c-1.152-.598-2.891-1.114-4.535-.292c-2.066 1.033-2.07 3.32-1.048 4.465c1.005 1.124 2.949 1.658 5.159.688c1.197-.525 2.704-1.287 3.706-1.794c.412-.208.739-.373.923-.46Z");
}

.kj60y6b9j {
  stop-color: var(--svg-color--ec4c5c, #EC4C5C);
}

.l8tyccbtp {
  stop-color: var(--svg-color--d12951, #D12951);
}

.lpdnf_b0o {
  stop-color: var(--svg-color--bb1865, #BB1865);
}

.mb_ri9bhy {
  stop-color: var(--svg-color--d24162, #D24162);
}

.mqj5dyuok {
  stop-color: var(--svg-color--c11451, #C11451);
  stop-opacity: 0;
}

.mrimfm3ol {
  stop-color: var(--svg-color--a80435, #A80435);
  stop-opacity: 0;
}

.ne1-ywb6l {
  fill: var(--svg-color--c4c4c4, #C4C4C4);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  d: path("m8.662 15.352l4.211 2.069c-.657.312-2.932 1.51-4.62 2.25c-2.112.927-3.91.4-4.816-.613c-.904-1.013-.91-3.062.96-3.996c1.516-.759 3.144-.291 4.265.29");
}

.nwc2uzbna {
  stop-color: var(--svg-color--a2304b, #A2304B);
  stop-opacity: 0;
}

.ptpuywr1j {
  stop-color: var(--svg-color--932128, #932128);
  stop-opacity: 0;
}

.pzvhaibnx {
  stop-color: var(--svg-color--c83065, #C83065);
}

.r0biv5bhk {
  stop-color: var(--svg-color--e04e6f, #E04E6F);
  stop-opacity: 0;
}

.sit9lobxd {
  stop-color: var(--svg-color--db1532, #DB1532);
}

.sjcpqcb9j {
  d: path("m8.662 15.352l4.211 2.069c-.657.312-2.932 1.51-4.62 2.25c-2.112.927-3.91.4-4.816-.613c-.904-1.013-.91-3.062.96-3.996c1.516-.759 3.144-.291 4.265.29");
}

.stlo64bwy {
  stop-color: var(--svg-color--97242a, #97242A);
}

.tub-zvbtm {
  stop-color: var(--svg-color--aa3244, #AA3244);
}

.u-07f5idp {
  stop-color: var(--svg-color--f75053, #F75053);
}

.u3h8mkb3k {
  stop-color: var(--svg-color--980129, #980129);
  stop-opacity: 0;
}

.u8kr8j20a {
  stop-color: var(--svg-color--c92d60, #C92D60);
}

.vx07dl_yr {
  d: path("m18.517 9.724l-.83-.395l5.32-2.612c1.185-.614 3.035-1.177 4.805-.292c.356.178.657.391.906.628c.527.463 1.217 1.372 1.217 2.968v6.764c.042.541-.18 1.932-1.018 2.709c-1.114 1.21-3.185 1.73-5.47.727c-1.206-.529-2.74-1.304-3.742-1.811c-.404-.204-.722-.365-.896-.448l-1.122-.533l.83-.407z");
}

.w1wx8dn-p {
  width: 6.915px;
  height: 12.99px;
  x: 12.604px;
  y: 7.112px;
  rx: 1.85px;
}

.xpk8s-30k {
  stop-color: var(--svg-color--a52548, #A52548);
}

.xqc8i55uj {
  stop-color: var(--svg-color--aa3244, #AA3244);
  stop-opacity: 0;
}

.y05g6wbyi {
  stop-color: var(--svg-color--f75053, #F75053);
  stop-opacity: 0;
}

.y1xw-vb1l {
  stop-color: var(--svg-color--c31867, #C31867);
}

.y4vrltb0r {
  stop-color: var(--svg-color--e04e6f, #E04E6F);
}

.yx7pws-tr {
  stop-color: var(--svg-color--ec4c5c, #EC4C5C);
  stop-opacity: 0;
}

.z7hvf9b8c {
  stop-color: var(--svg-color--db3665, #DB3665);
  stop-opacity: 0;
}

.zll07hy5k {
  stop-color: var(--svg-color--ec4953, #EC4953);
}

</style>

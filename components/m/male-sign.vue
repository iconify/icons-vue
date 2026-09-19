<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJs9b5u)"><rect fill="url(#ij9WRnd)" class="wexgjub6r"/><rect fill="url(#ip5LTFP)" class="wexgjub6r"/></g><g filter="url(#i4bILCS)"><path stroke="url(#iguRklP)" class="oowse_b7i"/></g><g filter="url(#i2nOiyb)"><path stroke="url(#ikIToNb)" class="zhpd08qdz"/></g><g filter="url(#iyo8whd)"><path class="qqdi4ib1w"/></g><g filter="url(#iOAym4G)"><path class="qlqnldpry"/></g><defs><filter id="iJs9b5u" width="28.875" height="28.875" x="2.289" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1681"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1681" result="effect2_innerShadow_18590_1681"/></filter><filter id="i4bILCS" width="5.5" height="28.375" x="25.727" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1681" stdDeviation="1"/></filter><filter id="i2nOiyb" width="27.281" height="5.5" x="3.003" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1681" stdDeviation="1"/></filter><filter id="iyo8whd" width="21.797" height="21.922" x="5.328" y="5.039" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1681" stdDeviation=".5"/></filter><filter id="iOAym4G" width="21.197" height="21.322" x="5.328" y="5.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1681"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1681" result="effect2_innerShadow_18590_1681"/></filter><linearGradient id="ij9WRnd" x1="16.227" x2="16.227" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iguRklP" x1="28.977" x2="28.977" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="ikIToNb" x1="28.691" x2="3.159" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="ip5LTFP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.946 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:male-sign" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.oowse_b7i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.477 4.563v22.875");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.qlqnldpry {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M20.907 6.04a1 1 0 1 0 0 2h1.672a.1.1 0 0 1 .072.17l-3.34 3.38a.1.1 0 0 1-.132.008a8 8 0 1 0 1.535 1.542a.1.1 0 0 1 .008-.132l3.232-3.272a.1.1 0 0 1 .171.07v1.53a1 1 0 1 0 2 0V7.039a1 1 0 0 0-1-1zm-6.579 5.92a6 6 0 1 1 0 12a6 6 0 0 1 0-12");
}

.qqdi4ib1w {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M20.907 6.04a1 1 0 1 0 0 2h1.672a.1.1 0 0 1 .072.17l-3.34 3.38a.1.1 0 0 1-.132.008a8 8 0 1 0 1.535 1.542a.1.1 0 0 1 .008-.132l3.232-3.272a.1.1 0 0 1 .171.07v1.53a1 1 0 1 0 2 0V7.039a1 1 0 0 0-1-1zm-6.579 5.92a6 6 0 1 1 0 12a6 6 0 0 1 0-12");
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.wexgjub6r {
  width: 27.875px;
  height: 27.875px;
  x: 2.289px;
  y: 2.063px;
  rx: 3.6px;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.zhpd08qdz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.753 3.875h21.782");
}

</style>

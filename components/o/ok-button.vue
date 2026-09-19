<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iMcOVAI)"><rect fill="url(#iCIS50b)" class="e6t-6p0wi"/><rect fill="url(#iHuHgml)" class="e6t-6p0wi"/></g><g filter="url(#iU3xVFc)"><path stroke="url(#i6D0j6b)" class="nu38pivva"/></g><g filter="url(#izbT3id)"><path stroke="url(#iK4uABc)" class="z-3fqacxc"/></g><path class="ji-so3bva"/><defs><linearGradient id="iCIS50b" x1="15.661" x2="15.661" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="i6D0j6b" x1="28.411" x2="28.411" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iK4uABc" x1="28.125" x2="2.594" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><filter id="iMcOVAI" width="28.875" height="28.875" x="1.723" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2450"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2450" result="effect2_innerShadow_18590_2450"/></filter><filter id="iU3xVFc" width="5.5" height="28.375" x="25.161" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2450" stdDeviation="1"/></filter><filter id="izbT3id" width="27.281" height="5.5" x="2.437" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2450" stdDeviation="1"/></filter><radialGradient id="iHuHgml" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.38 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ok-button" /></template>
<style>
.e6t-6p0wi {
  width: 27.875px;
  height: 27.875px;
  x: 1.723px;
  y: 2.063px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.ji-so3bva {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.856 8.984a4.89 4.89 0 0 0-4.89 4.89v4.228a4.89 4.89 0 0 0 9.781 0v-4.227a4.89 4.89 0 0 0-4.89-4.89m-2.14 4.89a2.14 2.14 0 0 1 4.281 0v4.228a2.14 2.14 0 0 1-4.281 0zM19.74 10.36a1.375 1.375 0 0 0-2.75 0v11.257a1.375 1.375 0 1 0 2.75 0V17.78c0-.034.013-.067.037-.091l.002-.002l.498-.52a.125.125 0 0 1 .195.019l3.345 5.2a1.375 1.375 0 1 0 2.313-1.488l-3.734-5.804a.125.125 0 0 1 .015-.154l3.446-3.597a1.375 1.375 0 0 0-1.986-1.903l-3.916 4.088a.125.125 0 0 1-.216-.086z");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.nu38pivva {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M27.91 4.563v22.875");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
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

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

.z-3fqacxc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.187 3.875h21.781");
}

</style>

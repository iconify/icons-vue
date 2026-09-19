<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWh1sQb)"><rect fill="url(#icOaROc)" class="iflfje1xi"/><rect fill="url(#izHDDeb)" class="iflfje1xi"/></g><g filter="url(#i8uJyBd)"><path stroke="url(#iHRaIQe)" class="s-eitpbpj"/></g><g filter="url(#iYHUgXv)"><path stroke="url(#itVKkZc)" class="af-a-45nu"/></g><path class="ot5os2dae"/><defs><linearGradient id="icOaROc" x1="15.661" x2="15.661" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iHRaIQe" x1="28.411" x2="28.411" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="itVKkZc" x1="28.125" x2="2.594" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><filter id="iWh1sQb" width="28.875" height="28.875" x="1.723" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2463"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2463" result="effect2_innerShadow_18590_2463"/></filter><filter id="i8uJyBd" width="5.5" height="28.375" x="25.161" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2463" stdDeviation="1"/></filter><filter id="iYHUgXv" width="27.281" height="5.5" x="2.437" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2463" stdDeviation="1"/></filter><radialGradient id="izHDDeb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.38 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:p-button" /></template>
<style>
.af-a-45nu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.187 3.75h21.781");
}

.ft5dv1b6b {
  fill: none;
}

.iflfje1xi {
  width: 27.875px;
  height: 27.875px;
  x: 1.723px;
  y: 1.938px;
  rx: 3.6px;
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.ot5os2dae {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.023 8.867a1.5 1.5 0 0 1 1.5-1.5h5.54c2.852 0 5.07 2.068 5.07 5c0 1.412-.523 2.68-1.47 3.593c-.943.908-2.222 1.384-3.6 1.384h-3.79a.25.25 0 0 0-.25.25v5.289a1.5 1.5 0 0 1-3 0zm3 5.227c0 .138.112.25.25.25h3.79c.685 0 1.192-.23 1.518-.545c.321-.31.552-.779.552-1.432c0-1.197-.795-2-2.07-2h-3.79a.25.25 0 0 0-.25.25z");
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.s-eitpbpj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M27.91 4.438v22.875");
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

</style>

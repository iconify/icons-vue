<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihaKq3b)"><rect fill="url(#ian3q2v)" class="czhhxob9r"/><rect fill="url(#iKQOhWd)" class="czhhxob9r"/></g><g filter="url(#iuXn99g)"><path stroke="url(#iXbNsQe)" class="vkrkhjbhm"/></g><g filter="url(#irhPE2X)"><path stroke="url(#iWqiYid)" class="vplyevb8i"/></g><g filter="url(#i13vqmd)"><path class="ezw-o1nyn"/></g><g filter="url(#ieELxzb)"><path class="qt1dt9brb"/></g><defs><filter id="ihaKq3b" width="28.875" height="28.875" x="1.855" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1391" result="effect2_innerShadow_18590_1391"/></filter><filter id="iuXn99g" width="5.5" height="28.375" x="25.293" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1391" stdDeviation="1"/></filter><filter id="irhPE2X" width="27.281" height="5.5" x="2.569" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1391" stdDeviation="1"/></filter><filter id="i13vqmd" width="20" height="16.624" x="5.793" y="7.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1391" stdDeviation=".5"/></filter><filter id="ieELxzb" width="19.4" height="16.024" x="5.793" y="8.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1391" result="effect2_innerShadow_18590_1391"/></filter><linearGradient id="ian3q2v" x1="15.793" x2="15.793" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iXbNsQe" x1="28.543" x2="28.543" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iWqiYid" x1="28.257" x2="2.725" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iKQOhWd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.512 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:next-track-button" /></template>
<style>
.czhhxob9r {
  width: 27.875px;
  height: 27.875px;
  x: 1.855px;
  y: 1.938px;
  rx: 3.6px;
}

.ezw-o1nyn {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M14.793 16.903a.028.028 0 0 0-.047-.02l-6.26 6.023c-.635.611-1.693.16-1.693-.72V9.564c0-.882 1.058-1.332 1.693-.72l6.26 6.022a.028.028 0 0 0 .047-.02V9.565c0-.882 1.058-1.332 1.693-.72l6.26 6.022a.028.028 0 0 0 .047-.02V9.375a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5v-5.472a.028.028 0 0 0-.047-.02l-6.26 6.023c-.635.611-1.693.16-1.693-.72z");
}

.ft5dv1b6b {
  fill: none;
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.pjb-fs-ow {
  stop-color: var(--svg-color--4878dd, #4878DD);
}

.pttsnab-v {
  stop-color: var(--svg-color--7dd8ff, #7DD8FF);
}

.qt1dt9brb {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M14.793 16.903a.028.028 0 0 0-.047-.02l-6.26 6.023c-.635.611-1.693.16-1.693-.72V9.564c0-.882 1.058-1.332 1.693-.72l6.26 6.022a.028.028 0 0 0 .047-.02V9.565c0-.882 1.058-1.332 1.693-.72l6.26 6.022a.028.028 0 0 0 .047-.02V9.375a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v13a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5v-5.472a.028.028 0 0 0-.047-.02l-6.26 6.023c-.635.611-1.693.16-1.693-.72z");
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

.vkrkhjbhm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.043 4.438v22.875");
}

.vplyevb8i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.32 3.75H27.1");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i1elrZb)"><rect fill="url(#iJWkeCb)" class="ureja0nlo"/><rect fill="url(#is7lbIb)" class="ureja0nlo"/></g><g filter="url(#i0bB6oH)"><path stroke="url(#iJmo6zO)" class="lzkto8b2i"/></g><g filter="url(#iSmoYZd)"><path stroke="url(#iv9KSJb)" class="o311fobps"/></g><g filter="url(#i17BU8c)"><path class="a2qyg0bqc"/></g><g filter="url(#ix3clyc)"><path class="izawd2beb"/></g><defs><filter id="i1elrZb" width="28.875" height="28.875" x="2.066" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_806" result="effect2_innerShadow_18590_806"/></filter><filter id="i0bB6oH" width="5.5" height="28.375" x="25.503" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_806" stdDeviation="1"/></filter><filter id="iSmoYZd" width="27.281" height="5.5" x="2.78" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_806" stdDeviation="1"/></filter><filter id="i17BU8c" width="14.63" height="22.224" x="8.685" y="4.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_806" stdDeviation=".5"/></filter><filter id="ix3clyc" width="13.63" height="21.224" x="9.085" y="5.552" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_806" result="effect2_innerShadow_18590_806"/></filter><linearGradient id="iJWkeCb" x1="16.003" x2="16.003" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iJmo6zO" x1="28.753" x2="28.753" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iv9KSJb" x1="28.467" x2="2.936" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="is7lbIb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:up-down-arrow" /></template>
<style>
.a2qyg0bqc {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M15.306 6.231a1 1 0 0 1 1.387 0l5.313 5.113c.648.624.207 1.72-.694 1.72H18.25a.25.25 0 0 0-.25.25v5.5c0 .138.112.25.25.25h3.063c.9 0 1.342 1.096.693 1.72l-5.313 5.113a1 1 0 0 1-1.387 0l-5.312-5.112c-.65-.625-.207-1.72.693-1.72h3.063a.25.25 0 0 0 .25-.25v-5.5a.25.25 0 0 0-.25-.25h-3.063c-.9 0-1.342-1.097-.693-1.721z");
}

.ft5dv1b6b {
  fill: none;
}

.izawd2beb {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M15.306 6.231a1 1 0 0 1 1.387 0l5.313 5.113c.648.624.207 1.72-.694 1.72H18.25a.25.25 0 0 0-.25.25v5.5c0 .138.112.25.25.25h3.063c.9 0 1.342 1.096.693 1.72l-5.313 5.113a1 1 0 0 1-1.387 0l-5.312-5.112c-.65-.625-.207-1.72.693-1.72h3.063a.25.25 0 0 0 .25-.25v-5.5a.25.25 0 0 0-.25-.25h-3.063c-.9 0-1.342-1.097-.693-1.721z");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.lzkto8b2i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.563v22.875");
}

.mqmvrj28a {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
}

.o311fobps {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.875h21.78");
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

.ureja0nlo {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 2.063px;
  rx: 3.6px;
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>

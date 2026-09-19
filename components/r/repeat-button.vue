<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iKhY5Bb" class="u6q2nibbs"/></defs><g class="ft5dv1b6b"><g filter="url(#iHp9AJe)"><rect fill="url(#iu6uuhx)" class="h0p06bbmt"/><rect fill="url(#idH8Edb)" class="h0p06bbmt"/></g><g filter="url(#iWaX0ie)"><path stroke="url(#iuoj85c)" class="kmlmbtlat"/></g><g filter="url(#i487nJe)"><path stroke="url(#iq7Akab)" class="do-ezeb8g"/></g><g filter="url(#iBXsxGd)" class="jyttb_bnu"><use href="#iKhY5Bb"/></g><g filter="url(#i18jPsd)" class="b-c38gb2l"><use href="#iKhY5Bb"/></g><defs><filter id="iHp9AJe" width="28.875" height="28.875" x="1.855" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1335" result="effect2_innerShadow_18590_1335"/></filter><filter id="iWaX0ie" width="5.5" height="28.375" x="25.293" y="2.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1335" stdDeviation="1"/></filter><filter id="i487nJe" width="27.281" height="5.5" x="2.569" y="1.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1335" stdDeviation="1"/></filter><filter id="iBXsxGd" width="22" height="19.989" x="4.789" y="6.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1335" stdDeviation=".5"/></filter><filter id="i18jPsd" width="21" height="18.989" x="5.189" y="6.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1335"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1335" result="effect2_innerShadow_18590_1335"/></filter><linearGradient id="iu6uuhx" x1="15.793" x2="15.793" y1="6.012" y2="39.265" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iuoj85c" x1="28.543" x2="28.543" y1="4.938" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iq7Akab" x1="28.257" x2="2.725" y1="4.5" y2="4.5" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="idH8Edb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.512 4.531)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:repeat-button" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.do-ezeb8g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.32 4.25H27.1");
}

.ft5dv1b6b {
  fill: none;
}

.h0p06bbmt {
  width: 27.875px;
  height: 27.875px;
  x: 1.855px;
  y: 2.438px;
  rx: 3.6px;
}

.jyttb_bnu {
  fill: var(--svg-color--579fff, #579FFF);
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.kmlmbtlat {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.043 4.938v22.875");
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

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.u6q2nibbs {
  d: path("m25.654 10.598l-3.4-3.108c-.238-.239-.654-.062-.664.281v1.268a.36.36 0 0 1-.364.364H11.36c-3.067.01-5.572 2.484-5.572 5.54v3.152a.36.36 0 0 0 .603.27l2.245-2.058a.33.33 0 0 0 .115-.25v-1.103a2.62 2.62 0 0 1 2.62-2.62l9.864.032c.198 0 .364.166.364.363v1.269c0 .343.405.53.655.29l3.4-3.118a.375.375 0 0 0 0-.572M5.924 22.151l3.4 3.108c.239.24.654.063.665-.28V23.71c0-.198.156-.364.364-.364h9.865c3.066-.01 5.571-2.485 5.571-5.54v-3.114a.36.36 0 0 0-.603-.27l-2.245 2.058a.33.33 0 0 0-.114.25v1.065a2.62 2.62 0 0 1-2.62 2.62l-9.865-.032a.37.37 0 0 1-.364-.364v-1.268c0-.343-.405-.53-.654-.29l-3.4 3.118a.375.375 0 0 0 0 .571");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>

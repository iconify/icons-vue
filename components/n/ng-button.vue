<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iS8bw6b" class="d6aqpyc6p"/></defs><g class="ft5dv1b6b"><g filter="url(#iPhSJee)"><rect fill="url(#iyqjvye)" class="j6gmv-c-w"/><rect fill="url(#iXa3xob)" class="j6gmv-c-w"/></g><g filter="url(#i4TWIHd)"><path stroke="url(#itOjDbc)" class="wz82-uw9i"/></g><g filter="url(#ixprdse)"><path stroke="url(#iXUO1xe)" class="udkwziwwy"/></g><g filter="url(#iIt3XJe)" class="jyttb_bnu"><use href="#iS8bw6b"/></g><g filter="url(#i8I5DPc)" class="b-c38gb2l"><use href="#iS8bw6b"/></g><defs><filter id="iPhSJee" width="28.875" height="28.875" x="1.934" y=".688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2422"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2422" result="effect2_innerShadow_18590_2422"/></filter><filter id="i4TWIHd" width="5.5" height="28.375" x="25.372" y="1.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2422" stdDeviation="1"/></filter><filter id="ixprdse" width="27.281" height="5.5" x="2.648" y=".75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2422" stdDeviation="1"/></filter><filter id="iIt3XJe" width="22" height="15.875" x="4.868" y="7.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2422" stdDeviation=".5"/></filter><filter id="i8I5DPc" width="21.4" height="15.275" x="4.868" y="8.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2422"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2422" result="effect2_innerShadow_18590_2422"/></filter><linearGradient id="iyqjvye" x1="15.872" x2="15.872" y1="5.262" y2="38.515" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="itOjDbc" x1="28.622" x2="28.622" y1="4.188" y2="27.063" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iXUO1xe" x1="28.336" x2="2.804" y1="3.75" y2="3.75" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iXa3xob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.59 3.781)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ng-button" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.d6aqpyc6p {
  d: path("M8.443 9.39a1.375 1.375 0 0 0-2.575.672v11.126a1.375 1.375 0 1 0 2.75 0v-5.38c0-.13.171-.174.234-.062l3.426 6.114a1.375 1.375 0 0 0 2.574-.672V10.063a1.375 1.375 0 1 0-2.75 0v5.38c0 .128-.17.173-.234.06zm12.82-.702a4.957 4.957 0 0 0-4.957 4.957v3.944a4.973 4.973 0 0 0 4.973 4.974h.547a4.04 4.04 0 0 0 4.042-4.043v-2.254c0-.76-.615-1.375-1.375-1.375h-2.307a1.375 1.375 0 0 0 0 2.75h.807c.07 0 .125.056.125.125v.754a1.29 1.29 0 0 1-1.292 1.293h-.547a2.223 2.223 0 0 1-2.223-2.224v-3.944a2.207 2.207 0 0 1 4.146-1.054l.083.152a1.375 1.375 0 1 0 2.416-1.313l-.082-.152a4.96 4.96 0 0 0-4.356-2.59");
}

.ft5dv1b6b {
  fill: none;
}

.j6gmv-c-w {
  width: 27.875px;
  height: 27.875px;
  x: 1.934px;
  y: 1.688px;
  rx: 3.6px;
}

.jyttb_bnu {
  fill: var(--svg-color--579fff, #579FFF);
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

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.udkwziwwy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.398 3.5H27.18");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.wz82-uw9i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.122 4.188v22.875");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>

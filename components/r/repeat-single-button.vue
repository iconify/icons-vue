<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iqgTQub" class="i2xo1cc_w"/></defs><g class="ft5dv1b6b"><g filter="url(#iucRbsc)"><rect fill="url(#iXwTqDe)" class="flyvdwbgx"/><rect fill="url(#izeVogg)" class="flyvdwbgx"/></g><g filter="url(#idaGZgb)"><path stroke="url(#i4J6ond)" class="bagbe-b4t"/></g><g filter="url(#iIr3FGb)"><path stroke="url(#iYEWnKb)" class="pn97xpb9z"/></g><g filter="url(#icu6LVb)" class="jyttb_bnu"><use href="#iqgTQub"/></g><g filter="url(#ifOgmWb)" class="b-c38gb2l"><use href="#iqgTQub"/></g><defs><filter id="iucRbsc" width="28.875" height="28.875" x="1.855" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1349"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1349" result="effect2_innerShadow_18590_1349"/></filter><filter id="idaGZgb" width="5.5" height="28.375" x="25.293" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1349" stdDeviation="1"/></filter><filter id="iIr3FGb" width="27.281" height="5.5" x="2.569" y="1.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1349" stdDeviation="1"/></filter><filter id="icu6LVb" width="22" height="20.503" x="4.789" y="5.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1349" stdDeviation=".5"/></filter><filter id="ifOgmWb" width="21" height="19.503" x="5.189" y="6.599" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1349"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1349" result="effect2_innerShadow_18590_1349"/></filter><linearGradient id="iXwTqDe" x1="15.793" x2="15.793" y1="5.887" y2="39.14" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="i4J6ond" x1="28.543" x2="28.543" y1="4.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iYEWnKb" x1="28.257" x2="2.725" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="izeVogg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.512 4.406)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:repeat-single-button" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.bagbe-b4t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.043 4.813v22.875");
}

.flyvdwbgx {
  width: 27.875px;
  height: 27.875px;
  x: 1.855px;
  y: 2.313px;
  rx: 3.6px;
}

.ft5dv1b6b {
  fill: none;
}

.i2xo1cc_w {
  d: path("m25.654 10.217l-3.4-3.109c-.238-.239-.654-.062-.664.281v1.268a.36.36 0 0 1-.364.364H11.36c-3.067.01-5.572 2.485-5.572 5.54v4.097c0 .24.32.354.492.19a4.75 4.75 0 0 1 2.264-1.208a.26.26 0 0 0 .207-.251v-2.817a2.62 2.62 0 0 1 2.62-2.62l9.864.032c.198 0 .364.166.364.364v1.268c0 .343.405.53.655.29l3.4-3.118a.375.375 0 0 0 0-.571m-11.486 9.798c-.19-.001-.313.203-.237.378a4.74 4.74 0 0 1 .375 2.286a.26.26 0 0 0 .257.286h5.655c3.066-.01 5.571-2.484 5.571-5.54V14.31a.36.36 0 0 0-.603-.27l-2.245 2.058a.33.33 0 0 0-.114.25v1.065a2.62 2.62 0 0 1-2.62 2.62zM12.79 22.25a3.251 3.251 0 1 1-6.504 0a3.251 3.251 0 0 1 6.503 0m-4.297-1.755a.5.5 0 0 0 .5.5h.027a.1.1 0 0 1 .1.1v2.626a.5.5 0 0 0 1 0v-3.226a.5.5 0 0 0-.5-.5h-.627a.5.5 0 0 0-.5.5");
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

.pn97xpb9z {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.32 4.125H27.1");
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

</style>

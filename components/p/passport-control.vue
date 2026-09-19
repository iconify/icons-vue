<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iGMpmxd" class="ggmko5nkl"/></defs><g class="ft5dv1b6b"><g filter="url(#iFDMv9d)"><rect fill="url(#idLgXPc)" class="q0w0nkbbo"/><rect fill="url(#iCTmPxe)" class="q0w0nkbbo"/></g><g filter="url(#iEdbokc)"><path stroke="url(#iCWwXsb)" class="el57ppqhu"/></g><g filter="url(#iOLwsgc)"><path stroke="url(#iVwoZ8b)" class="v694b959m"/></g><g filter="url(#it9jgzT)" class="jyttb_bnu"><use href="#iGMpmxd"/></g><g filter="url(#iVgYzkd)" class="b-c38gb2l"><use href="#iGMpmxd"/></g><defs><filter id="iFDMv9d" width="28.875" height="28.875" x="2.487" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_476" result="effect2_innerShadow_18590_476"/></filter><filter id="iEdbokc" width="5.5" height="28.375" x="25.924" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_476" stdDeviation="1"/></filter><filter id="iOLwsgc" width="27.281" height="5.5" x="3.2" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_476" stdDeviation="1"/></filter><filter id="it9jgzT" width="20.022" height="22.053" x="6.41" y="4.973" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_476" stdDeviation=".5"/></filter><filter id="iVgYzkd" width="18.822" height="20.853" x="7.01" y="5.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_476"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_476" result="effect2_innerShadow_18590_476"/></filter><linearGradient id="idLgXPc" x1="16.424" x2="16.424" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iCWwXsb" x1="29.174" x2="29.174" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iVwoZ8b" x1="28.888" x2="3.357" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iCTmPxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 28.143 4.156)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:passport-control" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.el57ppqhu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.674 4.563v22.875");
}

.ft5dv1b6b {
  fill: none;
}

.ggmko5nkl {
  d: path("M17.231 5.973a.5.5 0 0 0-.45.72l.58 1.19a.1.1 0 0 1-.09.144h-1.34a.5.5 0 0 0 0 1h8a.5.5 0 0 0 .5-.5V6.473a.5.5 0 0 0-.5-.5zm.7 4.054a.5.5 0 0 0-.5.5v.5c0 .394.09.784.267 1.148c.176.364.433.694.758.973c.326.278.711.5 1.136.65a4.04 4.04 0 0 0 2.679 0a3.6 3.6 0 0 0 1.135-.65c.325-.279.583-.61.759-.973c.176-.364.266-.755.266-1.149v-.5a.5.5 0 0 0-.5-.5zm-6-2a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-.5.5h-1.4a.1.1 0 0 0-.1.1v.766a.5.5 0 0 1-.75.433l-1.696-.98l-.052-.026l-.249-.142a.5.5 0 0 1-.252-.434V8.526a.5.5 0 0 1 .5-.5zm-1.5 4.875c0 .069.056.125.125.125h.75a.125.125 0 0 0 .125-.125v-3.75a.125.125 0 0 0-.125-.125H9.733a.125.125 0 0 0-.088.213l.64.64a.5.5 0 0 1 .146.354zm13.749 2.125a.5.5 0 0 1 .341.865l-7.576 7.08a.306.306 0 0 1-.514-.223v-3.387a.1.1 0 0 0-.17-.071l-2.319 2.306a1.5 1.5 0 0 1-1.058.437H8.91a1.5 1.5 0 0 1 0-3h3.314a.1.1 0 0 0 .07-.03l3.56-3.54a1.5 1.5 0 0 1 1.077-.437zm-7.749 10.316a.5.5 0 0 1 .155-.361l8-7.652a.5.5 0 0 1 .845.361v7.836a.5.5 0 0 1-.5.5h-8a.5.5 0 0 1-.5-.5z");
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

.q0w0nkbbo {
  width: 27.875px;
  height: 27.875px;
  x: 2.487px;
  y: 2.063px;
  rx: 3.6px;
}

.tcol3199r {
  stop-color: var(--svg-color--5cb7ff, #5CB7FF);
}

.tzz9ercjs {
  stop-color: var(--svg-color--639df4, #639DF4);
}

.v694b959m {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.95 3.875h21.782");
}

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>

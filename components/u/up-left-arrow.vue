<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isUediB)"><rect fill="url(#iAj6YMd)" class="jgqd2d7kb"/><rect fill="url(#iK13QUc)" class="jgqd2d7kb"/></g><g filter="url(#iMAeiGQ)"><path stroke="url(#inGGr8v)" class="c135xwwbn"/></g><g filter="url(#iO1IJyd)"><path stroke="url(#i12b0GY)" class="vw--dac9p"/></g><g filter="url(#ixjud0b)"><path class="fidbtpbri"/></g><g filter="url(#iU3o0Xd)"><path class="vjhocpvqp"/></g><defs><filter id="isUediB" width="28.875" height="28.875" x="2.066" y="1.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_792"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_792" result="effect2_innerShadow_18590_792"/></filter><filter id="iMAeiGQ" width="5.5" height="28.375" x="25.503" y="1.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_792" stdDeviation="1"/></filter><filter id="iO1IJyd" width="27.281" height="5.5" x="2.78" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_792" stdDeviation="1"/></filter><filter id="ixjud0b" width="16.603" height="16.603" x="8.119" y="7.824" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_792" stdDeviation=".5"/></filter><filter id="iU3o0Xd" width="15.603" height="15.603" x="8.519" y="8.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.819608 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_792"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_792" result="effect2_innerShadow_18590_792"/></filter><linearGradient id="iAj6YMd" x1="16.003" x2="16.003" y1="5.762" y2="39.015" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="inGGr8v" x1="28.753" x2="28.753" y1="4.688" y2="27.563" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="i12b0GY" x1="28.467" x2="2.936" y1="4.25" y2="4.25" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="iK13QUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.281)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:up-left-arrow" /></template>
<style>
.c135xwwbn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.688v22.875");
}

.fidbtpbri {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M9.119 9.578a.75.75 0 0 1 .754-.754l7.293.037a.75.75 0 0 1 .526 1.28l-1.917 1.917c-.126.127-.08.348.05.472l.018.018l7.586 7.586a1 1 0 0 1 0 1.414l-1.586 1.586a1 1 0 0 1-1.414 0l-7.586-7.586l-.018-.019c-.124-.13-.345-.176-.472-.049l-1.917 1.917a.75.75 0 0 1-1.28-.527z");
}

.ft5dv1b6b {
  fill: none;
}

.jgqd2d7kb {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 2.188px;
  rx: 3.6px;
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

.v8b118b2b {
  stop-color: var(--svg-color--7bd7ff, #7BD7FF);
  stop-opacity: 0;
}

.vjhocpvqp {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M9.119 9.578a.75.75 0 0 1 .754-.754l7.293.037a.75.75 0 0 1 .526 1.28l-1.917 1.917c-.126.127-.08.348.05.472l.018.018l7.586 7.586a1 1 0 0 1 0 1.414l-1.586 1.586a1 1 0 0 1-1.414 0l-7.586-7.586l-.018-.019c-.124-.13-.345-.176-.472-.049l-1.917 1.917a.75.75 0 0 1-1.28-.527z");
}

.vw--dac9p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 4h21.78");
}

.xaz-kzbvq {
  stop-color: var(--svg-color--7fd9ff, #7FD9FF);
}

</style>

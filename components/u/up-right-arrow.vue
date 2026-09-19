<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isCFgce)"><rect fill="url(#i6iN0ed)" class="rfy6e_r-r"/><rect fill="url(#i0dPjwd)" class="rfy6e_r-r"/></g><g filter="url(#iL9Pcuc)"><path stroke="url(#iWfBMab)" class="zyovjmgnw"/></g><g filter="url(#iP3kLxd)"><path stroke="url(#iaNREvc)" class="jhj8ddb7x"/></g><g filter="url(#iyB4PJe)"><path class="q88c3-b-w"/></g><g filter="url(#i0I4DMc)"><path class="kmrkt6bjy"/></g><defs><filter id="isCFgce" width="28.875" height="28.875" x="2.066" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.470588 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.34902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_708" result="effect2_innerShadow_18590_708"/></filter><filter id="iL9Pcuc" width="5.5" height="28.375" x="25.503" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_708" stdDeviation="1"/></filter><filter id="iP3kLxd" width="27.281" height="5.5" x="2.78" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_708" stdDeviation="1"/></filter><filter id="iyB4PJe" width="16.602" height="16.601" x="7.703" y="7.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_708" stdDeviation=".5"/></filter><filter id="i0I4DMc" width="15.602" height="15.601" x="8.103" y="8.174" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.854902 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_708"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_708" result="effect2_innerShadow_18590_708"/></filter><linearGradient id="i6iN0ed" x1="16.003" x2="16.003" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="tcol3199r"/><stop offset="1" class="pjb-fs-ow"/></linearGradient><linearGradient id="iWfBMab" x1="28.753" x2="28.753" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="xaz-kzbvq"/><stop offset="1" class="tzz9ercjs"/></linearGradient><linearGradient id="iaNREvc" x1="28.467" x2="2.936" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="pttsnab-v"/><stop offset="1" class="k8tg0e93k"/></linearGradient><radialGradient id="i0dPjwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.722 4.031)" gradientUnits="userSpaceOnUse"><stop class="mqmvrj28a"/><stop offset="1" class="v8b118b2b"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:up-right-arrow" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jhj8ddb7x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.53 3.75h21.78");
}

.k8tg0e93k {
  stop-color: var(--svg-color--5db6ff, #5DB6FF);
}

.kmrkt6bjy {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M23.304 9.58a1 1 0 0 0-1.005-1.006l-6.441.033c-.889.005-1.33 1.08-.702 1.707l1.493 1.493c.127.127.08.348-.05.472l-.018.018l-7.586 7.586a1 1 0 0 0 0 1.414l1.586 1.586a1 1 0 0 0 1.414 0l7.586-7.586l.018-.018c.124-.13.345-.176.472-.05l1.493 1.494c.628.628 1.703.186 1.707-.702z");
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

.q88c3-b-w {
  fill: var(--svg-color--579fff, #579FFF);
  d: path("M23.304 9.58a1 1 0 0 0-1.005-1.006l-6.441.033c-.889.005-1.33 1.08-.702 1.707l1.493 1.493c.127.127.08.348-.05.472l-.018.018l-7.586 7.586a1 1 0 0 0 0 1.414l1.586 1.586a1 1 0 0 0 1.414 0l7.586-7.586l.018-.018c.124-.13.345-.176.472-.05l1.493 1.494c.628.628 1.703.186 1.707-.702z");
}

.rfy6e_r-r {
  width: 27.875px;
  height: 27.875px;
  x: 2.066px;
  y: 1.938px;
  rx: 3.6px;
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

.zyovjmgnw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.253 4.438v22.875");
}

</style>

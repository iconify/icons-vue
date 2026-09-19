<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="i0ZHEjk" class="eh8xdqhiz"/></defs><g class="ft5dv1b6b"><g filter="url(#iI0WF6n)"><rect fill="url(#iIqmhXc)" class="pyvl0kbrt"/><rect fill="url(#igHeoTc)" class="pyvl0kbrt"/></g><g filter="url(#iEP70uL)"><path stroke="url(#i6fUazc)" class="cuelpuzns"/></g><g filter="url(#iZZUBUk)"><path stroke="url(#iI9s8De)" class="jmboxq4co"/></g><g filter="url(#ixHaZMd)" class="mzeqhufrl"><use href="#i0ZHEjk"/></g><g filter="url(#iWZEuHd)" class="b-c38gb2l"><use href="#i0ZHEjk"/></g><defs><filter id="iI0WF6n" width="29.875" height="28.875" x="1.723" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_420" result="effect2_innerShadow_18590_420"/></filter><filter id="iEP70uL" width="5.5" height="28.375" x="25.161" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_420" stdDeviation="1"/></filter><filter id="iZZUBUk" width="27.281" height="5.5" x="2.437" y="1.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_420" stdDeviation="1"/></filter><filter id="ixHaZMd" width="14.126" height="24" x="8.594" y="4.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_420" stdDeviation=".5"/></filter><filter id="iWZEuHd" width="12.925" height="22.8" x="9.194" y="4.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_420"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_420" result="effect2_innerShadow_18590_420"/></filter><linearGradient id="iIqmhXc" x1="15.661" x2="15.661" y1="5.887" y2="39.14" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="i6fUazc" x1="28.411" x2="28.411" y1="4.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iI9s8De" x1="28.125" x2="2.594" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="igHeoTc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.38 4.406)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:womens-room" /></template>
<style>
.b-c38gb2l {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
}

.cuelpuzns {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M27.91 4.813v22.875");
}

.eh8xdqhiz {
  d: path("M18.067 7.75a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m-5.375 3.438a2 2 0 0 0-1.933 1.486l-1.13 4.257a1 1 0 1 0 1.932.513l1.067-3.98a.3.3 0 0 1 .31-.223l.126.007a.47.47 0 0 1 .445.467q0 .003.003.004q.004 0 .004.004l-1.931 6.908a.5.5 0 0 0 .481.635h.96a.1.1 0 0 1 .1.1v4.856c0 .539.414 1.002.952 1.027a1 1 0 0 0 1.048-.999v-4.484a.5.5 0 1 1 1 0v4.456c0 .539.414 1.002.952 1.027a1 1 0 0 0 1.048-.999v-4.884a.1.1 0 0 1 .1-.1h.98a.5.5 0 0 0 .483-.632l-1.892-6.954a.455.455 0 0 1 .407-.45a.46.46 0 0 1 .494.335l1.057 3.885a1 1 0 1 0 1.93-.525l-1.16-4.262a2 2 0 0 0-1.93-1.476z");
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.jmboxq4co {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.187 4.125h21.781");
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.mzeqhufrl {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
}

.pyvl0kbrt {
  width: 27.875px;
  height: 27.875px;
  x: 1.723px;
  y: 2.313px;
  rx: 3.6px;
}

.s-kusnt3y {
  stop-color: var(--svg-color--8777d6, #8777D6);
}

.sefcefa1m {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
  stop-opacity: 0;
}

.sn77b5ppw {
  stop-color: var(--svg-color--9865ee, #9865EE);
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

</style>

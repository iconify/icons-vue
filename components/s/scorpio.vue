<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iCPLaYd)"><rect fill="url(#iMNVwdZ)" class="r5bp-typz"/><rect fill="url(#ibJhsXc)" class="r5bp-typz"/></g><g filter="url(#iEvoOXW)"><path stroke="url(#irfOwvx)" class="pf-8kcbsx"/></g><g filter="url(#iF3Qige)"><path stroke="url(#ivkANuf)" class="de260t8gq"/></g><g filter="url(#ixHfTVb)"><path class="rh4_2umhq"/></g><g filter="url(#iVEnK9c)"><path class="ga-s7ra1v"/></g><defs><filter id="iCPLaYd" width="29.875" height="28.875" x="2.301" y=".813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1236"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1236" result="effect2_innerShadow_18590_1236"/></filter><filter id="iEvoOXW" width="5.5" height="28.375" x="25.739" y="1.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1236" stdDeviation="1"/></filter><filter id="iF3Qige" width="27.281" height="5.5" x="3.015" y=".875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1236" stdDeviation="1"/></filter><filter id="ixHfTVb" width="25.752" height="20" x="3.78" y="5.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1236" stdDeviation=".5"/></filter><filter id="iVEnK9c" width="24.552" height="18.8" x="4.38" y="6.35" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1236"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1236" result="effect2_innerShadow_18590_1236"/></filter><linearGradient id="iMNVwdZ" x1="16.239" x2="16.239" y1="5.387" y2="38.64" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="irfOwvx" x1="28.989" x2="28.989" y1="4.313" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="ivkANuf" x1="28.703" x2="3.171" y1="3.875" y2="3.875" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="ibJhsXc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.958 3.906)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scorpio" /></template>
<style>
.de260t8gq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.765 3.625h21.781");
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.ga-s7ra1v {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("m28.33 18.42l-2-2.12a.76.76 0 0 0-.55-.24c-.21 0-.4.09-.55.24l-2 2.12c-.28.3-.27.78.03 1.06s.78.27 1.06-.03l.288-.3a.1.1 0 0 1 .172.069v2.051a1.5 1.5 0 0 1-3-.02v-10.5a3.996 3.996 0 0 0-6.924-2.724a.105.105 0 0 1-.152 0A4 4 0 0 0 11.78 6.75c-1.15 0-2.196.494-2.924 1.276a.105.105 0 0 1-.152 0A4 4 0 0 0 5.78 6.75c-.55 0-1 .45-1 1s.45 1 1 1c1.1 0 2 .9 2 2v13c0 .55.45 1 1 1s1-.45 1-1v-13c0-1.1.9-2 2-2s2 .9 2 2v13c0 .55.45 1 1 1s1-.45 1-1v-13c0-1.1.9-2 2-2s2 .9 2 2v10.5c0 1.93 1.57 3.5 3.5 3.5s3.5-1.57 3.5-3.5v-2.027a.1.1 0 0 1 .173-.069l.277.296a.75.75 0 0 0 1.06.04c.31-.29.32-.76.04-1.07");
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.pf-8kcbsx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.489 4.313v22.875");
}

.r5bp-typz {
  width: 27.875px;
  height: 27.875px;
  x: 2.301px;
  y: 1.813px;
  rx: 3.6px;
}

.rh4_2umhq {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("m28.33 18.42l-2-2.12a.76.76 0 0 0-.55-.24c-.21 0-.4.09-.55.24l-2 2.12c-.28.3-.27.78.03 1.06s.78.27 1.06-.03l.288-.3a.1.1 0 0 1 .172.069v2.051a1.5 1.5 0 0 1-3-.02v-10.5a3.996 3.996 0 0 0-6.924-2.724a.105.105 0 0 1-.152 0A4 4 0 0 0 11.78 6.75c-1.15 0-2.196.494-2.924 1.276a.105.105 0 0 1-.152 0A4 4 0 0 0 5.78 6.75c-.55 0-1 .45-1 1s.45 1 1 1c1.1 0 2 .9 2 2v13c0 .55.45 1 1 1s1-.45 1-1v-13c0-1.1.9-2 2-2s2 .9 2 2v13c0 .55.45 1 1 1s1-.45 1-1v-13c0-1.1.9-2 2-2s2 .9 2 2v10.5c0 1.93 1.57 3.5 3.5 3.5s3.5-1.57 3.5-3.5v-2.027a.1.1 0 0 1 .173-.069l.277.296a.75.75 0 0 0 1.06.04c.31-.29.32-.76.04-1.07");
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

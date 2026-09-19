<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iumKCbc)"><rect fill="url(#iiUzkCb)" class="hrne6_-xd"/><rect fill="url(#i6Y1v4d)" class="hrne6_-xd"/></g><g filter="url(#iwwBZpl)"><path stroke="url(#ir6N8qC)" class="l3v0m_dua"/></g><g filter="url(#i2osrvc)"><path stroke="url(#ixL4plu)" class="rph9k9bke"/></g><g filter="url(#iikdv5d)"><path class="dopwyv_-f"/></g><g filter="url(#in0HttZ)"><path class="dgsa55-tf"/></g><defs><filter id="iumKCbc" width="29.875" height="28.875" x="2.301" y="1.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1695"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1695" result="effect2_innerShadow_18590_1695"/></filter><filter id="iwwBZpl" width="5.5" height="28.375" x="25.739" y="1.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1695" stdDeviation="1"/></filter><filter id="i2osrvc" width="27.281" height="5.5" x="3.015" y="1.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1695" stdDeviation="1"/></filter><filter id="iikdv5d" width="24.031" height="25" x="4.22" y="3.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1695" stdDeviation=".5"/></filter><filter id="in0HttZ" width="22.831" height="23.8" x="4.82" y="4.162" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1695"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1695" result="effect2_innerShadow_18590_1695"/></filter><linearGradient id="iiUzkCb" x1="16.239" x2="16.239" y1="5.637" y2="38.89" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="ir6N8qC" x1="28.989" x2="28.989" y1="4.563" y2="27.438" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="ixL4plu" x1="28.703" x2="3.171" y1="4.125" y2="4.125" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="i6Y1v4d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.958 4.156)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:transgender-symbol" /></template>
<style>
.dgsa55-tf {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M10.282 4.563a1 1 0 1 1 0 2H8.747a.1.1 0 0 0-.072.17l1.696 1.741a.1.1 0 0 0 .143.001l1.03-1.03a1 1 0 1 1 1.414 1.414l-1.05 1.05a.1.1 0 0 0-.002.141l.725.744c.034.036.09.04.131.012a5.97 5.97 0 0 1 3.489-1.118a5.97 5.97 0 0 1 3.518 1.139c.041.03.098.025.133-.011l3.914-4.084a.1.1 0 0 0-.072-.17h-1.54a1 1 0 0 1 0-2h4.047a1 1 0 0 1 1 1V9.61a1 1 0 1 1-2 0V8.374a.1.1 0 0 0-.172-.07l-3.8 3.966a.1.1 0 0 0-.011.125a6.002 6.002 0 0 1-3.933 9.195a.1.1 0 0 0-.084.1v1.772a.1.1 0 0 0 .1.1h1.4a1 1 0 1 1 0 2h-1.4a.1.1 0 0 0-.1.1v.9a1 1 0 1 1-2 0v-.9a.1.1 0 0 0-.1-.1h-1.4a1 1 0 1 1 0-2h1.4a.1.1 0 0 0 .1-.1V21.69a.1.1 0 0 0-.084-.1a6.002 6.002 0 0 1-3.912-9.225a.1.1 0 0 0-.011-.127l-.75-.77a.1.1 0 0 0-.143-.001l-.929.929a1 1 0 0 1-1.414-1.415l.95-.95a.1.1 0 0 0 0-.14L7.392 8.28a.1.1 0 0 0-.171.07v1.275a1 1 0 1 1-2 0V5.563a1 1 0 0 1 1-1zm1.969 11.125a4 4 0 1 0 8 0a4 4 0 0 0-8 0");
}

.dopwyv_-f {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M10.282 4.563a1 1 0 1 1 0 2H8.747a.1.1 0 0 0-.072.17l1.696 1.741a.1.1 0 0 0 .143.001l1.03-1.03a1 1 0 1 1 1.414 1.414l-1.05 1.05a.1.1 0 0 0-.002.141l.725.744c.034.036.09.04.131.012a5.97 5.97 0 0 1 3.489-1.118a5.97 5.97 0 0 1 3.518 1.139c.041.03.098.025.133-.011l3.914-4.084a.1.1 0 0 0-.072-.17h-1.54a1 1 0 0 1 0-2h4.047a1 1 0 0 1 1 1V9.61a1 1 0 1 1-2 0V8.374a.1.1 0 0 0-.172-.07l-3.8 3.966a.1.1 0 0 0-.011.125a6.002 6.002 0 0 1-3.933 9.195a.1.1 0 0 0-.084.1v1.772a.1.1 0 0 0 .1.1h1.4a1 1 0 1 1 0 2h-1.4a.1.1 0 0 0-.1.1v.9a1 1 0 1 1-2 0v-.9a.1.1 0 0 0-.1-.1h-1.4a1 1 0 1 1 0-2h1.4a.1.1 0 0 0 .1-.1V21.69a.1.1 0 0 0-.084-.1a6.002 6.002 0 0 1-3.912-9.225a.1.1 0 0 0-.011-.127l-.75-.77a.1.1 0 0 0-.143-.001l-.929.929a1 1 0 0 1-1.414-1.415l.95-.95a.1.1 0 0 0 0-.14L7.392 8.28a.1.1 0 0 0-.171.07v1.275a1 1 0 1 1-2 0V5.563a1 1 0 0 1 1-1zm1.969 11.125a4 4 0 1 0 8 0a4 4 0 0 0-8 0");
}

.fitiklbqp {
  stop-color: var(--svg-color--7764c6, #7764C6);
}

.ft5dv1b6b {
  fill: none;
}

.hrne6_-xd {
  width: 27.875px;
  height: 27.875px;
  x: 2.301px;
  y: 2.063px;
  rx: 3.6px;
}

.jlbvuvbtx {
  stop-color: var(--svg-color--9a6ceb, #9A6CEB);
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.l3v0m_dua {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.489 4.563v22.875");
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
}

.rph9k9bke {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.765 3.875h21.781");
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

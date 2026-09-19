<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLhPoQd)"><rect fill="url(#itFUVDc)" class="wv-zasezo"/><rect fill="url(#iGTIbqb)" class="wv-zasezo"/></g><g filter="url(#iijfgde)"><path stroke="url(#iyLwd3Y)" class="jxv0d4x5h"/></g><g filter="url(#ivMu6Sb)"><path stroke="url(#iVMHhMc)" class="xaj1i0bwq"/></g><g filter="url(#iU2JxQg)"><path class="yl5578bfh"/></g><g filter="url(#iGrPunc)"><path class="d5o29abjh"/></g><defs><filter id="iLhPoQd" width="29.875" height="28.875" x="2.301" y="1.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.298039 0 0 0 0 0.235294 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1292"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.211765 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1292" result="effect2_innerShadow_18590_1292"/></filter><filter id="iijfgde" width="5.5" height="28.375" x="25.739" y="2.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1292" stdDeviation="1"/></filter><filter id="ivMu6Sb" width="27.281" height="5.5" x="3.015" y="1.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1292" stdDeviation="1"/></filter><filter id="iU2JxQg" width="22" height="22.004" x="5.656" y="5.248" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1292" stdDeviation=".5"/></filter><filter id="iGrPunc" width="20.8" height="20.804" x="6.256" y="5.848" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1292"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1292" result="effect2_innerShadow_18590_1292"/></filter><linearGradient id="itFUVDc" x1="16.239" x2="16.239" y1="5.887" y2="39.14" gradientUnits="userSpaceOnUse"><stop class="sn77b5ppw"/><stop offset="1" class="fitiklbqp"/></linearGradient><linearGradient id="iyLwd3Y" x1="28.989" x2="28.989" y1="4.813" y2="27.688" gradientUnits="userSpaceOnUse"><stop class="ygaxn_bkp"/><stop offset="1" class="s-kusnt3y"/></linearGradient><linearGradient id="iVMHhMc" x1="28.703" x2="3.171" y1="4.375" y2="4.375" gradientUnits="userSpaceOnUse"><stop class="ka-x5u-uy"/><stop offset="1" class="jlbvuvbtx"/></linearGradient><radialGradient id="iGTIbqb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.958 4.406)" gradientUnits="userSpaceOnUse"><stop class="mgmxs0b3v"/><stop offset="1" class="sefcefa1m"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pisces" /></template>
<style>
.d5o29abjh {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("M25.656 15.252h-3.852a.1.1 0 0 1-.099-.108c.24-2.65 1.336-5.13 3.21-7.222a.998.998 0 1 0-1.49-1.33a14.8 14.8 0 0 0-2.77 4.44a14.1 14.1 0 0 0-.962 4.127a.1.1 0 0 1-.1.093h-5.884a.1.1 0 0 1-.1-.093a14 14 0 0 0-.963-4.127c-.63-1.61-1.56-3.11-2.75-4.45a.998.998 0 1 0-1.49 1.33c1.874 2.102 2.97 4.582 3.21 7.222a.1.1 0 0 1-.099.108H7.656c-.55 0-1 .45-1 1s.45 1 1 1h3.851a.1.1 0 0 1 .1.108c-.24 2.65-1.337 5.13-3.211 7.222a1 1 0 0 0 .08 1.41c.19.19.43.27.67.27c.28 0 .55-.11.75-.33c1.19-1.34 2.12-2.83 2.76-4.44c.528-1.33.855-2.719.963-4.127a.1.1 0 0 1 .1-.093h5.884a.1.1 0 0 1 .1.093a14 14 0 0 0 .963 4.127a14.9 14.9 0 0 0 2.76 4.44c.2.22.47.33.75.33c.24 0 .47-.08.66-.25c.41-.37.45-1 .08-1.41c-1.875-2.101-2.97-4.582-3.21-7.222a.1.1 0 0 1 .098-.108h3.852c.55 0 1-.45 1-1s-.45-1.01-1-1.01");
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

.jxv0d4x5h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.489 4.813v22.875");
}

.ka-x5u-uy {
  stop-color: var(--svg-color--a672ff, #A672FF);
}

.mgmxs0b3v {
  stop-color: var(--svg-color--bb8dff, #BB8DFF);
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

.wv-zasezo {
  width: 27.875px;
  height: 27.875px;
  x: 2.301px;
  y: 2.313px;
  rx: 3.6px;
}

.xaj1i0bwq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.765 4.125h21.781");
}

.ygaxn_bkp {
  stop-color: var(--svg-color--ae7eff, #AE7EFF);
}

.yl5578bfh {
  fill: var(--svg-color--6a4ebe, #6A4EBE);
  d: path("M25.656 15.252h-3.852a.1.1 0 0 1-.099-.108c.24-2.65 1.336-5.13 3.21-7.222a.998.998 0 1 0-1.49-1.33a14.8 14.8 0 0 0-2.77 4.44a14.1 14.1 0 0 0-.962 4.127a.1.1 0 0 1-.1.093h-5.884a.1.1 0 0 1-.1-.093a14 14 0 0 0-.963-4.127c-.63-1.61-1.56-3.11-2.75-4.45a.998.998 0 1 0-1.49 1.33c1.874 2.102 2.97 4.582 3.21 7.222a.1.1 0 0 1-.099.108H7.656c-.55 0-1 .45-1 1s.45 1 1 1h3.851a.1.1 0 0 1 .1.108c-.24 2.65-1.337 5.13-3.211 7.222a1 1 0 0 0 .08 1.41c.19.19.43.27.67.27c.28 0 .55-.11.75-.33c1.19-1.34 2.12-2.83 2.76-4.44c.528-1.33.855-2.719.963-4.127a.1.1 0 0 1 .1-.093h5.884a.1.1 0 0 1 .1.093a14 14 0 0 0 .963 4.127a14.9 14.9 0 0 0 2.76 4.44c.2.22.47.33.75.33c.24 0 .47-.08.66-.25c.41-.37.45-1 .08-1.41c-1.875-2.101-2.97-4.582-3.21-7.222a.1.1 0 0 1 .098-.108h3.852c.55 0 1-.45 1-1s-.45-1.01-1-1.01");
}

</style>

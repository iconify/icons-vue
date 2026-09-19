<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSDoWIe)"><rect fill="url(#iDjFMzx)" class="gdxcnh9ok"/><rect fill="url(#i5CmOPe)" class="gdxcnh9ok"/><rect fill="url(#itsuV7s)" class="gdxcnh9ok"/></g><rect fill="url(#iswZy2b)" class="gdxcnh9ok"/><g filter="url(#iljFRTp)"><path class="wowfy0twx"/></g><path fill="url(#iHk2aev)" class="bl36ew1yn"/><path fill="url(#iPEFvqc)" class="bl36ew1yn"/><g filter="url(#isT6H6k)"><rect transform="rotate(45.013 16.645 17.183)" class="zyotfy7yp"/></g><g filter="url(#i4ll3rm)"><rect transform="rotate(45.013 19.512 18.808)" class="pjaeotb1g"/></g><g filter="url(#iUHEB1d)"><path stroke="url(#ioy5M9b)" class="qkin2hbcq"/></g><g filter="url(#iVZia2d)"><path stroke="url(#iRZ1Vnc)" class="s2yi_lexi"/></g><defs><linearGradient id="iDjFMzx" x1="3.758" x2="8.227" y1="29.781" y2="29.781" gradientUnits="userSpaceOnUse"><stop offset=".343" class="pv-k_k-2k"/><stop offset="1" class="xd8ul3brx"/></linearGradient><linearGradient id="i5CmOPe" x1="10.211" x2="9.852" y1="29.953" y2="29.953" gradientUnits="userSpaceOnUse"><stop offset=".154" class="qozxvvlmn"/><stop offset="1" class="v13f_hbxb"/></linearGradient><linearGradient id="itsuV7s" x1="2.055" x2="2.898" y1="29.125" y2="29.125" gradientUnits="userSpaceOnUse"><stop class="xkg0usbth"/><stop offset="1" class="lvsm0ze3r"/></linearGradient><linearGradient id="iswZy2b" x1="7.008" x2="7.008" y1="30.031" y2="29.887" gradientUnits="userSpaceOnUse"><stop class="bgmaylbmf"/><stop offset="1" class="w0u3d-jgk"/></linearGradient><linearGradient id="iHk2aev" x1="2.273" x2="8.445" y1="25.813" y2="25.813" gradientUnits="userSpaceOnUse"><stop offset=".06" class="bos8pccou"/><stop offset="1" class="okytdpcna"/></linearGradient><linearGradient id="ioy5M9b" x1="15.25" x2="17.266" y1="20.063" y2="18" gradientUnits="userSpaceOnUse"><stop class="a3t16xsqz"/><stop offset=".241" class="cgov9ebeg"/><stop offset=".591" class="cgov9ebeg"/><stop offset="1" class="ej4c7s0zn"/></linearGradient><linearGradient id="iRZ1Vnc" x1="18.125" x2="20.141" y1="21.742" y2="19.679" gradientUnits="userSpaceOnUse"><stop class="a3t16xsqz"/><stop offset=".241" class="cgov9ebeg"/><stop offset=".591" class="cgov9ebeg"/><stop offset="1" class="ej4c7s0zn"/></linearGradient><filter id="iSDoWIe" width="7.987" height="2.987" x="2.223" y="27.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.501961 0 0 0 0 0.25098 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17204"/></filter><filter id="iljFRTp" width="30.408" height="15.131" x="-.227" y="16.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-2.5" dy="2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.505882 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17204"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.5" dy="1.5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.443137 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17204" result="effect2_innerShadow_18_17204"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.309804 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_17204" result="effect3_innerShadow_18_17204"/></filter><filter id="isT6H6k" width="3.441" height="3.191" x="14.383" y="17.215" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.219608 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17204"/></filter><filter id="i4ll3rm" width="3.441" height="3.191" x="17.25" y="18.84" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.219608 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17204"/></filter><filter id="iUHEB1d" width="2.688" height="2.672" x="14.656" y="17.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17204" stdDeviation=".125"/></filter><filter id="iVZia2d" width="2.688" height="2.672" x="17.531" y="19.351" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17204" stdDeviation=".125"/></filter><radialGradient id="iPEFvqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.34375 4.15617 0 28.195 30.031)" gradientUnits="userSpaceOnUse"><stop class="hogp10b6i"/><stop offset="1" class="x0qe3lbhg"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mans-shoe" /></template>
<style>
.a3t16xsqz {
  stop-color: var(--svg-color--873c70, #873C70);
}

.bgmaylbmf {
  stop-color: var(--svg-color--893a7a, #893A7A);
}

.bl36ew1yn {
  d: path("M2.273 19.75v7.125c0 .138.112.25.25.25h9.135a2.71 2.71 0 0 1 2.71 2.71c0 .108.087.196.196.196h15.4c.11 0 .201-.088.204-.199l.001-.033c.02-.705.07-2.526-.349-4.236c-.875-3.579-3.53-4.188-7.515-5c-2.691-.55-5.026-1.891-6.455-2.908c-.569-.405-1.24-.655-1.937-.655h-8.89a2.75 2.75 0 0 0-2.75 2.75");
}

.bos8pccou {
  stop-color: var(--svg-color--7a5047, #7A5047);
}

.cgov9ebeg {
  stop-color: var(--svg-color--9c7675, #9C7675);
}

.ej4c7s0zn {
  stop-color: var(--svg-color--9c7675, #9C7675);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gdxcnh9ok {
  width: 7.938px;
  height: 2.938px;
  x: 2.273px;
  y: 27.094px;
  rx: 0.15px;
}

.hogp10b6i {
  stop-color: var(--svg-color--c78877, #C78877);
}

.lvsm0ze3r {
  stop-color: var(--svg-color--725f60, #725F60);
  stop-opacity: 0;
}

.okytdpcna {
  stop-color: var(--svg-color--914e49, #914E49);
  stop-opacity: 0;
}

.pjaeotb1g {
  width: 1.36px;
  height: 3.596px;
  x: 19.512px;
  y: 18.808px;
  fill: var(--svg-color--825751, #825751);
  rx: 0.68px;
}

.pv-k_k-2k {
  stop-color: var(--svg-color--653d43, #653D43);
}

.qkin2hbcq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m15.156 19.844l1.688-1.672");
}

.qozxvvlmn {
  stop-color: var(--svg-color--926970, #926970);
}

.s2yi_lexi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m18.031 21.523l1.688-1.672");
}

.v13f_hbxb {
  stop-color: var(--svg-color--926970, #926970);
  stop-opacity: 0;
}

.w0u3d-jgk {
  stop-color: var(--svg-color--893a7a, #893A7A);
  stop-opacity: 0;
}

.wowfy0twx {
  fill: var(--svg-color--b5666b, #B5666B);
  d: path("M2.273 19.75v7.125c0 .138.112.25.25.25h9.135a2.71 2.71 0 0 1 2.71 2.71c0 .108.087.196.196.196h15.4c.11 0 .201-.088.204-.199l.001-.033c.02-.705.07-2.526-.349-4.236c-.875-3.579-3.53-4.188-7.515-5c-2.691-.55-5.026-1.891-6.455-2.908c-.569-.405-1.24-.655-1.937-.655h-8.89a2.75 2.75 0 0 0-2.75 2.75");
}

.x0qe3lbhg {
  stop-color: var(--svg-color--ba706f, #BA706F);
  stop-opacity: 0;
}

.xd8ul3brx {
  stop-color: var(--svg-color--8c4f69, #8C4F69);
}

.xkg0usbth {
  stop-color: var(--svg-color--725f60, #725F60);
}

.zyotfy7yp {
  width: 1.36px;
  height: 3.596px;
  x: 16.645px;
  y: 17.183px;
  fill: var(--svg-color--825751, #825751);
  rx: 0.68px;
}

</style>

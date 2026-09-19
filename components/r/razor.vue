<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJ1roFb)"><rect fill="url(#irGlGmv)" transform="rotate(45 19.516 8.938)" class="mr25ei8eb"/><rect fill="url(#iZXQrlf)" transform="rotate(45 19.516 8.938)" class="mr25ei8eb"/></g><g filter="url(#iUW4cMd)"><rect fill="url(#iT9Dkjc)" transform="rotate(45 7.188 22.703)" class="lim88juzz"/></g><g filter="url(#iPxu1Tc)"><rect fill="url(#iPx7qOb)" transform="rotate(45 16.762 1.106)" class="yjugq8t3j"/></g><g filter="url(#ix0sZ6b)"><rect transform="rotate(45 17.094 4.281)" class="cemeytbsc"/></g><g filter="url(#iPj46Hc)"><rect transform="rotate(45 15.375 6.047)" class="dllzhmr_d"/></g><defs><filter id="iJ1roFb" width="21.07" height="21.07" x="1.916" y="9.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.482353 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.498039 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26035" result="effect2_innerShadow_18_26035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.419608 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_26035" result="effect3_innerShadow_18_26035"/></filter><filter id="iUW4cMd" width="5.257" height="5.257" x="3.923" y="23.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.372549 0 0 0 0 0.984314 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.552941 0 0 0 0 0.933333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26035" result="effect2_innerShadow_18_26035"/></filter><filter id="iPxu1Tc" width="19.18" height="19.18" x="11.576" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.713726 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.517647 0 0 0 0 0.866667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_26035" result="effect2_innerShadow_18_26035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.584314 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_26035" result="effect3_innerShadow_18_26035"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.462745 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="effect3_innerShadow_18_26035" result="effect4_innerShadow_18_26035"/></filter><filter id="ix0sZ6b" width="11.834" height="11.834" x="16.32" y="4.202" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.839216 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26035"/></filter><filter id="iPj46Hc" width="11.834" height="11.834" x="14.602" y="5.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".35"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.847059 0 0 0 0 0.890196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_26035"/></filter><linearGradient id="irGlGmv" x1="22.275" x2="22.275" y1="8.938" y2="34.438" gradientUnits="userSpaceOnUse"><stop class="fqnt9dcpg"/><stop offset="1" class="bupz5dx2u"/></linearGradient><linearGradient id="iZXQrlf" x1="22.631" x2="22.631" y1="12.937" y2="15.103" gradientUnits="userSpaceOnUse"><stop class="b5kd56dcd"/><stop offset="1" class="l067s9bfe"/></linearGradient><linearGradient id="iT9Dkjc" x1="8.93" x2="8.889" y1="22.703" y2="28.404" gradientUnits="userSpaceOnUse"><stop class="ffndsbcpk"/><stop offset="1" class="zr2m_kivx"/></linearGradient><linearGradient id="iPx7qOb" x1="27.006" x2="27.006" y1="1.106" y2="9.138" gradientUnits="userSpaceOnUse"><stop class="ggo8982ri"/><stop offset="1" class="sz87ncrdf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:razor" /></template>
<style>
.b5kd56dcd {
  stop-color: var(--svg-color--2f7beb, #2F7BEB);
}

.bupz5dx2u {
  stop-color: var(--svg-color--4384c7, #4384C7);
}

.cemeytbsc {
  width: 15.529px;
  height: 1.547px;
  x: 17.094px;
  y: 4.281px;
  fill: var(--svg-color--ac9abe, #AC9ABE);
  rx: 0.773px;
}

.dllzhmr_d {
  width: 15.529px;
  height: 1.547px;
  x: 15.375px;
  y: 6.047px;
  fill: var(--svg-color--ac99bf, #AC99BF);
  rx: 0.773px;
}

.ffndsbcpk {
  stop-color: var(--svg-color--2fdcff, #2FDCFF);
}

.fqnt9dcpg {
  stop-color: var(--svg-color--4787ee, #4787EE);
}

.ft5dv1b6b {
  fill: none;
}

.ggo8982ri {
  stop-color: var(--svg-color--499ffd, #499FFD);
}

.l067s9bfe {
  stop-color: var(--svg-color--2f7beb, #2F7BEB);
  stop-opacity: 0;
}

.lim88juzz {
  width: 3.486px;
  height: 5.425px;
  x: 7.188px;
  y: 22.703px;
  rx: 1.743px;
}

.mr25ei8eb {
  width: 5.519px;
  height: 25.5px;
  x: 19.516px;
  y: 8.938px;
  rx: 2.25px;
}

.sz87ncrdf {
  stop-color: var(--svg-color--4685da, #4685DA);
}

.yjugq8t3j {
  width: 20.489px;
  height: 8.032px;
  x: 16.762px;
  y: 1.106px;
  rx: 2.4px;
}

.zr2m_kivx {
  stop-color: var(--svg-color--2e9cf6, #2E9CF6);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i14g87B)" class="nmm_brpmu"/><circle fill="url(#intqXLe)" class="nmm_brpmu"/><circle fill="url(#iCFuBgc)" class="nmm_brpmu"/><g filter="url(#ifimx6c)"><path fill="url(#iDaZgdb)" clip-rule="evenodd" class="bdvdaccyf"/></g><g filter="url(#iLApMtu)" class="e3fsewyjy"><path stroke="url(#i2EtATd)" class="roqj2t7bq"/><path stroke="url(#iY58hdT)" class="roqj2t7bq"/></g><defs><linearGradient id="i14g87B" x1="15.688" x2="15.688" y1="25.689" y2="29.474" gradientUnits="userSpaceOnUse"><stop class="yscs58b3z"/><stop offset="1" class="xok0bwbut"/></linearGradient><linearGradient id="iDaZgdb" x1="16.18" x2="16.18" y1="2.064" y2="22.892" gradientUnits="userSpaceOnUse"><stop class="udgx1acma"/><stop offset="1" class="c368ti0ea"/></linearGradient><linearGradient id="i2EtATd" x1="23.043" x2="18.325" y1="6.443" y2="10.5" gradientUnits="userSpaceOnUse"><stop offset=".103" class="ol8a7jcdk"/><stop offset="1" class="dolejbbjl"/></linearGradient><linearGradient id="iY58hdT" x1="19.208" x2="19.208" y1="20.693" y2="12.467" gradientUnits="userSpaceOnUse"><stop class="sh3a69b4y"/><stop offset="1" class="i10wvyb7y"/></linearGradient><radialGradient id="intqXLe" cx="0" cy="0" r="1" gradientTransform="rotate(-43.835 40.93 -7.873)scale(1.84384 1.62111)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="qmbfq_f-e"/></radialGradient><radialGradient id="iCFuBgc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21874 -3.2999 6.7691 13.188 25.064)" gradientUnits="userSpaceOnUse"><stop class="fo1jvnaaz"/><stop offset="1" class="c0w1gewvz"/></radialGradient><filter id="ifimx6c" width="16.672" height="22.811" x="8.219" y=".831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.768627 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1817"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.67451 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1817" result="effect2_innerShadow_18590_1817"/></filter><filter id="iLApMtu" width="16.36" height="21.817" x="8.826" y="1.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1817" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-question-mark" /></template>
<style>
.bdvdaccyf {
  fill-rule: evenodd;
  d: path("M15.413 6.654c-.946.225-1.45.655-1.736 1.05c-.32.44-.458.965-.458 1.407a2.5 2.5 0 0 1-5 0c0-2.793 1.716-6.34 6.134-7.344l.098-.02c2.888-.536 5.41.255 7.18 1.983c1.703 1.662 2.51 3.99 2.51 6.256c0 2.253-.647 4.092-2.117 5.653c-1.012 1.075-2.355 1.943-3.852 2.762v1.991a2.5 2.5 0 1 1-5 0v-3.5a2.5 2.5 0 0 1 1.362-2.225c2.088-1.068 3.207-1.773 3.85-2.455c.483-.513.757-1.072.757-2.226c0-1.14-.41-2.1-1.002-2.678c-.516-.504-1.347-.897-2.726-.654");
}

.c0w1gewvz {
  stop-color: var(--svg-color--d1ccdc, #D1CCDC);
  stop-opacity: 0;
}

.c368ti0ea {
  stop-color: var(--svg-color--ccc2e3, #CCC2E3);
}

.dolejbbjl {
  stop-color: var(--svg-color--f6f4f9, #F6F4F9);
  stop-opacity: 0;
}

.e3fsewyjy {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ei-1_194g {
  stop-color: var(--svg-color--fffeff, #FFFEFF);
}

.fo1jvnaaz {
  stop-color: var(--svg-color--d1ccdc, #D1CCDC);
}

.ft5dv1b6b {
  fill: none;
}

.i10wvyb7y {
  stop-color: var(--svg-color--efe8ff, #EFE8FF);
  stop-opacity: 0;
}

.nmm_brpmu {
  cx: 15.688px;
  cy: 26.974px;
  r: 2.5px;
}

.ol8a7jcdk {
  stop-color: var(--svg-color--f6f4f9, #F6F4F9);
}

.qmbfq_f-e {
  stop-color: var(--svg-color--e7defb, #E7DEFB);
  stop-opacity: 0;
}

.roqj2t7bq {
  d: path("M11.326 8.583c0-1.828 1.138-4.203 4.355-4.906c4.47-.797 7.005 2.375 7.005 5.78c0 3.407-1.918 4.798-6.208 6.907v4.006");
}

.sh3a69b4y {
  stop-color: var(--svg-color--efe8ff, #EFE8FF);
}

.udgx1acma {
  stop-color: var(--svg-color--dad6e3, #DAD6E3);
}

.xok0bwbut {
  stop-color: var(--svg-color--c0ade6, #C0ADE6);
}

.yscs58b3z {
  stop-color: var(--svg-color--ece6f8, #ECE6F8);
}

</style>

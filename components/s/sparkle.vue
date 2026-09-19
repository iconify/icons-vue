<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihNIEoe)"><rect fill="url(#i60Dcdc)" class="af4z61f0l"/><rect fill="url(#ipkcgJO)" class="af4z61f0l"/></g><g filter="url(#iXl9Qjc)"><path stroke="url(#iIKfz6t)" class="yhu4ftb8i"/></g><g filter="url(#iWFgwTd)"><path stroke="url(#iWuiaQm)" class="yphcv9b4h"/></g><g filter="url(#icg6TYY)"><path class="luepn4rem"/></g><g filter="url(#ign1J4c)"><path class="kjcmn-jdl"/></g><defs><filter id="ihNIEoe" width="30.375" height="29.375" x="1.379" y=".938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.176471 0 0 0 0 0.521569 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2119"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.490196 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2119" result="effect2_innerShadow_18590_2119"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.356863 0 0 0 0 0.905882 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18590_2119" result="effect3_innerShadow_18590_2119"/></filter><filter id="iXl9Qjc" width="5.5" height="28.375" x="25.317" y="1.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2119" stdDeviation="1"/></filter><filter id="iWFgwTd" width="27.281" height="5.5" x="2.593" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2119" stdDeviation="1"/></filter><filter id="icg6TYY" width="23.409" height="23.409" x="4.112" y="4.171" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_2119" stdDeviation=".5"/></filter><filter id="ign1J4c" width="22.209" height="22.209" x="4.712" y="4.771" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.886275 0 0 0 0 0.968627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_2119"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.988235 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_2119" result="effect2_innerShadow_18590_2119"/></filter><linearGradient id="i60Dcdc" x1="15.817" x2="15.817" y1="5.512" y2="38.765" gradientUnits="userSpaceOnUse"><stop class="dm5pz02wr"/><stop offset="1" class="whunseb7r"/></linearGradient><linearGradient id="iIKfz6t" x1="28.567" x2="28.567" y1="4.438" y2="27.313" gradientUnits="userSpaceOnUse"><stop class="bd1uexb0j"/><stop offset="1" class="e7ccriz7m"/></linearGradient><linearGradient id="iWuiaQm" x1="28.281" x2="2.749" y1="4" y2="4" gradientUnits="userSpaceOnUse"><stop class="fscnvmo3e"/><stop offset="1" class="rzis-4b0g"/></linearGradient><radialGradient id="ipkcgJO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 1.46876 -1.71548 -1.82495 27.536 4.031)" gradientUnits="userSpaceOnUse"><stop class="qigmwq70y"/><stop offset="1" class="f9zwc6a2t"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sparkle" /></template>
<style>
.af4z61f0l {
  width: 27.875px;
  height: 27.875px;
  x: 1.879px;
  y: 1.938px;
  rx: 3.6px;
}

.bd1uexb0j {
  stop-color: var(--svg-color--74fca8, #74FCA8);
}

.dm5pz02wr {
  stop-color: var(--svg-color--5ad98f, #5AD98F);
}

.e7ccriz7m {
  stop-color: var(--svg-color--61db90, #61DB90);
}

.f9zwc6a2t {
  stop-color: var(--svg-color--80ffb3, #80FFB3);
  stop-opacity: 0;
}

.fscnvmo3e {
  stop-color: var(--svg-color--66f39d, #66F39D);
}

.ft5dv1b6b {
  fill: none;
}

.kjcmn-jdl {
  fill: var(--svg-color--fcf2ff, #FCF2FF);
  d: path("m17 7.922l-.703-2.393c-.141-.478-.819-.478-.96 0l-.704 2.393a10 10 0 0 1-6.77 6.77l-2.392.703c-.478.141-.478.819 0 .96l2.393.704a10 10 0 0 1 6.769 6.769l.704 2.393c.141.478.819.478.96 0L17 23.828a10 10 0 0 1 6.769-6.769l2.392-.704a.5.5 0 0 0 0-.96l-2.392-.704A10 10 0 0 1 17 7.922");
}

.luepn4rem {
  fill: var(--svg-color--53bb7d, #53BB7D);
  d: path("m17 7.922l-.703-2.393c-.141-.478-.819-.478-.96 0l-.704 2.393a10 10 0 0 1-6.77 6.77l-2.392.703c-.478.141-.478.819 0 .96l2.393.704a10 10 0 0 1 6.769 6.769l.704 2.393c.141.478.819.478.96 0L17 23.828a10 10 0 0 1 6.769-6.769l2.392-.704a.5.5 0 0 0 0-.96l-2.392-.704A10 10 0 0 1 17 7.922");
}

.qigmwq70y {
  stop-color: var(--svg-color--80ffb3, #80FFB3);
}

.rzis-4b0g {
  stop-color: var(--svg-color--60e496, #60E496);
}

.whunseb7r {
  stop-color: var(--svg-color--51c685, #51C685);
}

.yhu4ftb8i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M28.067 4.438v22.875");
}

.yphcv9b4h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.343 3.75h21.782");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDTTiuc)"><path fill="url(#iynvs9g)" class="ohqszdheu"/></g><g filter="url(#ibm4xSh)"><path fill="url(#iNmJG8c)" class="g08rqdb1d"/></g><g filter="url(#iGRyadz)"><path fill="url(#i6lI6yV)" class="n-2dxqbsb"/></g><g filter="url(#ij5XOPc)"><path fill="url(#imtHMve)" class="spt3cobzn"/><path fill="url(#iMzd2nO)" class="spt3cobzn"/><path fill="url(#itAjaZr)" class="spt3cobzn"/></g><g filter="url(#iNORG8d)"><path fill="url(#iZcqp8c)" class="znbap1btx"/></g><g filter="url(#ivhIwad)"><path fill="url(#izcun0c)" class="u81ut11dg"/></g><defs><linearGradient id="iynvs9g" x1="9.313" x2="16.501" y1="25.72" y2="27.72" gradientUnits="userSpaceOnUse"><stop class="km1ru7bba"/><stop offset="1" class="cqgqz_m7q"/></linearGradient><linearGradient id="iNmJG8c" x1="28.34" x2="24.578" y1="22.32" y2="14.31" gradientUnits="userSpaceOnUse"><stop class="xz6p5fbxs"/><stop offset="1" class="os7tzbb6m"/></linearGradient><linearGradient id="i6lI6yV" x1="16.001" x2="10.501" y1="6.219" y2="11.407" gradientUnits="userSpaceOnUse"><stop offset=".215" class="eyh9edueb"/><stop offset="1" class="pxrcosb6i"/></linearGradient><linearGradient id="imtHMve" x1="10.152" x2="4.62" y1="14.93" y2="26.524" gradientUnits="userSpaceOnUse"><stop class="yg7omgb4d"/><stop offset="1" class="zg62n_1qx"/></linearGradient><linearGradient id="iMzd2nO" x1="4.62" x2="7.629" y1="28.337" y2="25.772" gradientUnits="userSpaceOnUse"><stop class="jt4rflb4c"/><stop offset="1" class="h3imf7b5s"/></linearGradient><linearGradient id="itAjaZr" x1="11.767" x2="11.136" y1="19.422" y2="19.576" gradientUnits="userSpaceOnUse"><stop offset=".263" class="pfp3lcbrt"/><stop offset="1" class="jhrmm1bvh"/></linearGradient><linearGradient id="iZcqp8c" x1="28.605" x2="16.967" y1="25.551" y2="25.551" gradientUnits="userSpaceOnUse"><stop class="nrw4shbgn"/><stop offset="1" class="e896n3y2b"/></linearGradient><linearGradient id="izcun0c" x1="22.861" x2="16.939" y1="13.654" y2="3.715" gradientUnits="userSpaceOnUse"><stop class="nrw4shbgn"/><stop offset="1" class="ban4eccja"/></linearGradient><filter id="iDTTiuc" width="9.48" height="6.65" x="5.572" y="21.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.541176 0 0 0 0 0.439216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1900"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.372549 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1900" result="effect2_innerShadow_18590_1900"/></filter><filter id="ibm4xSh" width="9.708" height="8.788" x="20.853" y="14.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.65098 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1900"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.219608 0 0 0 0 0.376471 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1900" result="effect2_innerShadow_18590_1900"/></filter><filter id="iGRyadz" width="8.832" height="10.582" x="7.97" y="3.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.4 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1900"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.352941 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1900" result="effect2_innerShadow_18590_1900"/></filter><filter id="ij5XOPc" width="9.952" height="14.723" x="2.188" y="13.614" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.686275 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1900"/></filter><filter id="iNORG8d" width="14.651" height="10.308" x="15.532" y="19.819" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.376471 0 0 0 0 0.67451 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1900"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.733333 0 0 0 0 0.458824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1900" result="effect2_innerShadow_18590_1900"/></filter><filter id="ivhIwad" width="12.753" height="11.967" x="11.842" y="2.907" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.705882 0 0 0 0 0.454902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1900"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.94902 0 0 0 0 0.654902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1900" result="effect2_innerShadow_18590_1900"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:recycling-symbol" /></template>
<style>
.ban4eccja {
  stop-color: var(--svg-color--46d791, #46D791);
}

.cqgqz_m7q {
  stop-color: var(--svg-color--306b72, #306B72);
}

.e896n3y2b {
  stop-color: var(--svg-color--4fd7a5, #4FD7A5);
}

.eyh9edueb {
  stop-color: var(--svg-color--2d5267, #2D5267);
}

.ft5dv1b6b {
  fill: none;
}

.g08rqdb1d {
  d: path("m24.012 22.857l5.85-.66l.2-.54l-.1-.68l-3.27-6.31c-.28-.54-.95-.76-1.5-.47l-3.49 1.81c-.54.28-.76.95-.47 1.5z");
}

.h3imf7b5s {
  stop-color: var(--svg-color--44c89b, #44C89B);
  stop-opacity: 0;
}

.jhrmm1bvh {
  stop-color: var(--svg-color--63f5ad, #63F5AD);
  stop-opacity: 0;
}

.jt4rflb4c {
  stop-color: var(--svg-color--5ba48b, #5BA48B);
}

.km1ru7bba {
  stop-color: var(--svg-color--549f8d, #549F8D);
}

.n-2dxqbsb {
  d: path("m13.032 3.717l3.52 4.72l-3.21 5.09c-.33.52-1.01.68-1.53.35l-3.32-2.09c-.52-.33-.68-1.01-.35-1.53l3.79-6.01l.53-.43z");
}

.nrw4shbgn {
  stop-color: var(--svg-color--53e2a9, #53E2A9);
}

.ohqszdheu {
  d: path("m7.932 22.187l-2.11 5.49l.38.43l.64.22h7.1c.61 0 1.11-.5 1.11-1.11v-3.93c0-.61-.5-1.11-1.11-1.11h-6.01z");
}

.os7tzbb6m {
  stop-color: var(--svg-color--318270, #318270);
}

.pfp3lcbrt {
  stop-color: var(--svg-color--63f5ad, #63F5AD);
}

.pxrcosb6i {
  stop-color: var(--svg-color--2a6e67, #2A6E67);
}

.spt3cobzn {
  d: path("m11.872 20.347l-1.66-6.32a.554.554 0 0 0-.73-.38l-6.14 2.24c-.45.17-.49.79-.07 1.02l.928.49a.15.15 0 0 1 .063.202l-1.771 3.388c-.44.84-.4 1.84.11 2.64l2.2 3.48c.48.77 1.33 1.23 2.24 1.23c-.49 0-.88-.39-.88-.88c0-.15.04-.29.1-.41l3.47-6.607a.15.15 0 0 1 .202-.064l1.148.601c.42.23.91-.17.79-.63");
}

.u81ut11dg {
  d: path("m22.462 7.917l1.04-.6c.42-.24.93.12.83.58l-1.37 6.39c-.07.32-.4.51-.71.41l-6.23-1.97a.555.555 0 0 1-.11-1.01l1.25-.73l-3.82-6.58a.9.9 0 0 0-.29-.3a.887.887 0 0 0-1.21.28a2.64 2.64 0 0 1 2.23-1.23h4.11c.94 0 1.82.5 2.29 1.32z");
}

.xz6p5fbxs {
  stop-color: var(--svg-color--1e6c52, #1E6C52);
}

.yg7omgb4d {
  stop-color: var(--svg-color--4edf9f, #4EDF9F);
}

.zg62n_1qx {
  stop-color: var(--svg-color--4bd3a1, #4BD3A1);
}

.znbap1btx {
  d: path("M29.882 20.827a.884.884 0 0 1-.79 1.29l-7.61-.04l.01-1.45c0-.48-.57-.74-.93-.41l-4.85 4.38c-.24.22-.24.6 0 .82l4.82 4.41c.36.33.93.08.93-.41v-1.2l3.98.02c.94 0 1.82-.49 2.3-1.31l2.08-3.55c.46-.78.48-1.74.06-2.55");
}

</style>

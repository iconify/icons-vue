<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ikqk27d)" class="crkrc46po"/><circle fill="url(#iWXhxKe)" class="crkrc46po"/><circle fill="url(#i3JS3Vc)" class="crkrc46po"/><g filter="url(#iTHpgqt)"><path fill="url(#iLXWiOe)" class="n_80_jt5l"/></g><path fill="url(#ipyp05K)" class="n_80_jt5l"/><g filter="url(#iD5FOhc)"><path class="y1r8m8j1u"/></g><defs><linearGradient id="ikqk27d" x1="16" x2="16" y1="25.811" y2="29.596" gradientUnits="userSpaceOnUse"><stop class="yscs58b3z"/><stop offset="1" class="xok0bwbut"/></linearGradient><linearGradient id="iLXWiOe" x1="16" x2="16" y1="2.13" y2="22.623" gradientUnits="userSpaceOnUse"><stop class="lzqee4b8i"/><stop offset="1" class="o2jgj1hgn"/></linearGradient><linearGradient id="ipyp05K" x1="17.147" x2="17.147" y1="22.623" y2="19.25" gradientUnits="userSpaceOnUse"><stop class="zpq7lkqjj"/><stop offset="1" class="h0fpuyuli"/></linearGradient><radialGradient id="iWXhxKe" cx="0" cy="0" r="1" gradientTransform="rotate(-43.835 41.237 -8.2)scale(1.84384 1.62111)" gradientUnits="userSpaceOnUse"><stop class="ei-1_194g"/><stop offset="1" class="qmbfq_f-e"/></radialGradient><radialGradient id="i3JS3Vc" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 1.21875 -3.29992 6.76908 13.5 25.186)" gradientUnits="userSpaceOnUse"><stop class="fo1jvnaaz"/><stop offset="1" class="c0w1gewvz"/></radialGradient><filter id="iTHpgqt" width="6.75" height="20.969" x="12.5" y="1.654" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.933333 0 0 0 0 0.92549 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18590_1828"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.741176 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18590_1828" result="effect2_innerShadow_18590_1828"/></filter><filter id="iD5FOhc" width="5" height="21.832" x="14.736" y="1.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18590_1828" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-exclamation-mark" /></template>
<style>
.c0w1gewvz {
  stop-color: var(--svg-color--d1ccdc, #D1CCDC);
  stop-opacity: 0;
}

.crkrc46po {
  cx: 16px;
  cy: 27.096px;
  r: 2.5px;
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

.h0fpuyuli {
  stop-color: var(--svg-color--c1b9d4, #C1B9D4);
  stop-opacity: 0;
}

.lzqee4b8i {
  stop-color: var(--svg-color--e0dcea, #E0DCEA);
}

.n_80_jt5l {
  d: path("M13.5 4.154a2.5 2.5 0 0 1 5 0v15.969a2.5 2.5 0 1 1-5 0z");
}

.o2jgj1hgn {
  stop-color: var(--svg-color--cabfe1, #CABFE1);
}

.qmbfq_f-e {
  stop-color: var(--svg-color--e7defb, #E7DEFB);
  stop-opacity: 0;
}

.xok0bwbut {
  stop-color: var(--svg-color--c0ade6, #C0ADE6);
}

.y1r8m8j1u {
  stroke: var(--svg-color--f4effe, #F4EFFE);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.236 20.555V3.723");
}

.yscs58b3z {
  stop-color: var(--svg-color--ece6f8, #ECE6F8);
}

.zpq7lkqjj {
  stop-color: var(--svg-color--c1b9d4, #C1B9D4);
}

</style>

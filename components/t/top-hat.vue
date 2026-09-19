<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#icq3yOd)"><path fill="url(#iKyQ8Uc)" class="ufu34n38y"/></g><g filter="url(#ipWVwid)"><path class="i3r_svbtn"/></g><g filter="url(#izJeUhe)"><path fill="url(#iGjoo8d)" class="zoauhqbhm"/><path fill="url(#iW5T08c)" class="zoauhqbhm"/></g><g filter="url(#i6WQDNd)"><path fill="url(#iwCoFkb)" class="h9uqjkbiz"/><path fill="url(#ij4CXHd)" class="h9uqjkbiz"/><path fill="url(#ilp63bd)" class="h9uqjkbiz"/><path fill="url(#iKA3rMc)" class="h9uqjkbiz"/></g><g filter="url(#iTBX7yc)"><path class="x0lp3vwgu"/></g><g filter="url(#iBWkanc)"><path fill="url(#idB7C0l)" class="dr-cffb9x"/></g><defs><filter id="icq3yOd" width="28.063" height="13.438" x="1.719" y="16.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.396078 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17508"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.160784 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17508" result="effect2_innerShadow_18_17508"/></filter><filter id="ipWVwid" width="19.488" height="10.375" x="6.24" y="16.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17508" stdDeviation=".5"/></filter><filter id="izJeUhe" width="20.436" height="21.656" x="6.767" y="3.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.247059 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17508"/></filter><filter id="i6WQDNd" width="17.238" height="6.473" x="7.364" y="19.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.12549 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17508"/></filter><filter id="iTBX7yc" width="17.577" height="4.813" x="7.211" y="6.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17508" stdDeviation=".75"/></filter><filter id="iBWkanc" width="5.83" height="18.594" x="19.938" y="3.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17508" stdDeviation=".75"/></filter><linearGradient id="iKyQ8Uc" x1="16" x2="16" y1="17.031" y2="27.563" gradientUnits="userSpaceOnUse"><stop offset=".211" class="g9727y26m"/><stop offset="1" class="d1_ds-bjz"/></linearGradient><linearGradient id="iGjoo8d" x1="15.984" x2="15.984" y1="3.938" y2="25.594" gradientUnits="userSpaceOnUse"><stop offset=".421" class="q47baub5c"/><stop offset="1" class="n5lo4vfdu"/></linearGradient><linearGradient id="iwCoFkb" x1="10.375" x2="22.75" y1="21.187" y2="25" gradientUnits="userSpaceOnUse"><stop class="zgwbeiihi"/><stop offset="1" class="hc5pkwb7i"/></linearGradient><linearGradient id="iKA3rMc" x1="7.364" x2="11.375" y1="23.406" y2="23.406" gradientUnits="userSpaceOnUse"><stop class="flpxoxbff"/><stop offset="1" class="g001jqxve"/></linearGradient><linearGradient id="idB7C0l" x1="23.594" x2="22.853" y1="5.156" y2="20.75" gradientUnits="userSpaceOnUse"><stop class="t3b9pvbzy"/><stop offset="1" class="g12a7-bwo"/></linearGradient><radialGradient id="iW5T08c" cx="0" cy="0" r="1" gradientTransform="matrix(.75 -10.81252 4.6823 .32478 24.875 20.938)" gradientUnits="userSpaceOnUse"><stop class="rm_l-cc8e"/><stop offset="1" class="icwbj-05h"/></radialGradient><radialGradient id="ij4CXHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.75 -11.4063 0 20.469 21.094)" gradientUnits="userSpaceOnUse"><stop class="zznpspl7g"/><stop offset="1" class="ium0gwbhr"/></radialGradient><radialGradient id="ilp63bd" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.71875 -7.16957 0 22.437 20.312)" gradientUnits="userSpaceOnUse"><stop class="zem2-wbhe"/><stop offset="1" class="u7h-wfk7e"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:top-hat" /></template>
<style>
.d1_ds-bjz {
  stop-color: var(--svg-color--523b5e, #523B5E);
}

.dr-cffb9x {
  d: path("M21.438 20.75L22 5.156c2.05 0 2.354 2.042 2.25 3.063l-.437 10.844c-.45 1.1-1.771 1.583-2.375 1.687");
}

.flpxoxbff {
  stop-color: var(--svg-color--ba2d43, #BA2D43);
}

.ft5dv1b6b {
  fill: none;
}

.g001jqxve {
  stop-color: var(--svg-color--ba2d43, #BA2D43);
  stop-opacity: 0;
}

.g12a7-bwo {
  stop-color: var(--svg-color--4d4455, #4D4455);
}

.g9727y26m {
  stop-color: var(--svg-color--333135, #333135);
}

.h9uqjkbiz {
  d: path("M7.364 19.321c.509 1.259 1.837 2.398 3.683 2.398h10.031c1.794 0 3.057-1.108 3.524-2.363l-.201 3.414c-.094 1.586-1.245 2.824-3.323 2.824H11.047c-2.188 0-3.386-1.238-3.48-2.824z");
}

.hc5pkwb7i {
  stop-color: var(--svg-color--e12e84, #E12E84);
}

.i3r_svbtn {
  fill: var(--svg-color--3a1333, #3A1333);
  d: path("m7.24 17.469l.328 5.551c.093 1.586 1.291 2.824 3.479 2.824h10.031c2.078 0 3.23-1.238 3.323-2.824l.327-5.551z");
}

.icwbj-05h {
  stop-color: var(--svg-color--4c4653, #4C4653);
  stop-opacity: 0;
}

.ium0gwbhr {
  stop-color: var(--svg-color--fe4f93, #FE4F93);
  stop-opacity: 0;
}

.n5lo4vfdu {
  stop-color: var(--svg-color--43354b, #43354B);
}

.q47baub5c {
  stop-color: var(--svg-color--534262, #534262);
}

.rm_l-cc8e {
  stop-color: var(--svg-color--4c4653, #4C4653);
}

.t3b9pvbzy {
  stop-color: var(--svg-color--70657c, #70657C);
}

.u7h-wfk7e {
  stop-color: var(--svg-color--ff4c99, #FF4C99);
  stop-opacity: 0;
}

.ufu34n38y {
  d: path("M2.219 23.031c0-3.313 2.967-6 6.281-6h14.984c3.314 0 6.297 2.687 6.297 6v.938c0 3.313-2.672 6-6.437 6H8.797c-3.813 0-6.578-2.687-6.578-6z");
}

.x0lp3vwgu {
  fill: var(--svg-color--574965, #574965);
  d: path("M8.711 7.875h14.577v1.813H8.711z");
}

.zem2-wbhe {
  stop-color: var(--svg-color--ff4c99, #FF4C99);
}

.zgwbeiihi {
  stop-color: var(--svg-color--eb3469, #EB3469);
}

.zoauhqbhm {
  d: path("M11.047 25.594c-2.188 0-3.386-1.238-3.48-2.824L6.782 9.438c-.054-1.102-.009-3.279 1.078-4.391c1.085-1.11 2.034-1.11 2.822-1.11h10.607c.788 0 1.737 0 2.821 1.11c1.088 1.112 1.133 3.289 1.079 4.39L24.4 22.77c-.093 1.586-1.245 2.824-3.323 2.824z");
}

.zznpspl7g {
  stop-color: var(--svg-color--fe4f93, #FE4F93);
}

</style>

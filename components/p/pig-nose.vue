<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ikYdPac)"><path fill="url(#izJQvkd)" class="e_j3ocbmm"/><path fill="url(#iqm9yYd)" class="e_j3ocbmm"/><path fill="url(#iciKj6b)" class="e_j3ocbmm"/><g filter="url(#iDgGIzd)"><path fill="url(#isOwkqb)" clip-rule="evenodd" class="vk9p9db7a"/></g><path fill="url(#io4qcKc)" class="h7chfx87x"/><path stroke="url(#iMddbue)" class="ipwj6sb4o"/><path stroke="url(#ivHQKbc)" class="ipwj6sb4o"/><path fill="url(#iwdnZKc)" class="ji9st6dwc"/><path stroke="url(#i6rEuqc)" class="s4i4zxnjz"/><path stroke="url(#iYM5Qac)" class="s4i4zxnjz"/><g filter="url(#iVmZjpc)"><path stroke="url(#iM4tgoc)" class="zves6ucjo"/></g><g filter="url(#iHpZIde)"><path stroke="url(#iC5nN0b)" class="xu5028djw"/></g></g><defs><linearGradient id="izJQvkd" x1="16.625" x2="16.625" y1="8.75" y2="27" gradientUnits="userSpaceOnUse"><stop class="t548e9bhn"/><stop offset="1" class="q5q095skb"/></linearGradient><linearGradient id="iMddbue" x1="4.906" x2="12.25" y1="20.75" y2="14.469" gradientUnits="userSpaceOnUse"><stop class="bqkoarjxa"/><stop offset="1" class="eo7i18boh"/></linearGradient><linearGradient id="ivHQKbc" x1="13.266" x2="10.734" y1="12.609" y2="16.016" gradientUnits="userSpaceOnUse"><stop class="t699csbqu"/><stop offset="1" class="eo7i18boh"/></linearGradient><linearGradient id="i6rEuqc" x1="16.906" x2="24.25" y1="20.75" y2="14.469" gradientUnits="userSpaceOnUse"><stop class="bqkoarjxa"/><stop offset="1" class="eo7i18boh"/></linearGradient><linearGradient id="iYM5Qac" x1="25.266" x2="22.734" y1="12.609" y2="16.016" gradientUnits="userSpaceOnUse"><stop class="t699csbqu"/><stop offset="1" class="eo7i18boh"/></linearGradient><linearGradient id="iM4tgoc" x1="19.313" x2="18.7" y1="22.281" y2="15.724" gradientUnits="userSpaceOnUse"><stop class="e87g1xiaj"/><stop offset=".359" class="v7regbb_u"/><stop offset="1" class="eaxjz4ocb"/></linearGradient><linearGradient id="iC5nN0b" x1="7.562" x2="6.95" y1="22.281" y2="15.724" gradientUnits="userSpaceOnUse"><stop class="e87g1xiaj"/><stop offset=".359" class="v7regbb_u"/><stop offset="1" class="eaxjz4ocb"/></linearGradient><radialGradient id="iqm9yYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 24.5625 -31.655 0 16 8.25)" gradientUnits="userSpaceOnUse"><stop offset=".588" class="m-97rcbob"/><stop offset=".847" class="z8tq47bnr"/></radialGradient><radialGradient id="iciKj6b" cx="0" cy="0" r="1" gradientTransform="matrix(-17.25 0 0 -14.4973 18.813 18.625)" gradientUnits="userSpaceOnUse"><stop offset=".891" class="w4y2v1bsw"/><stop offset="1" class="icxftsb3h"/></radialGradient><radialGradient id="isOwkqb" cx="0" cy="0" r="1" gradientTransform="rotate(140.972 10.732 9.915)scale(4.14341 37.6194)" gradientUnits="userSpaceOnUse"><stop class="u0y0ggq7g"/><stop offset="1" class="q_w05_-5h"/></radialGradient><radialGradient id="io4qcKc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 0 0 9.65104 10.219 18.188)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="k3-y9hhvs"/><stop offset="1" class="krzvm_bou"/></radialGradient><radialGradient id="iwdnZKc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40625 0 0 9.65104 22.219 18.188)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="k3-y9hhvs"/><stop offset="1" class="krzvm_bou"/></radialGradient><filter id="iDgGIzd" width="15.794" height="15.75" x="14.5" y="6.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3099" stdDeviation=".5"/></filter><filter id="iVmZjpc" width="3.796" height="7.894" x="19.501" y="14.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3099" stdDeviation=".25"/></filter><filter id="iHpZIde" width="3.796" height="7.894" x="7.751" y="14.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3099" stdDeviation=".25"/></filter><clipPath id="ikYdPac"><path class="mydvbytws"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pig-nose" /></template>
<style>
.bqkoarjxa {
  stop-color: var(--svg-color--fc8bad, #FC8BAD);
}

.e_j3ocbmm {
  d: path("M30 18.79C29.89 11.17 23.66 6 16 6S2.11 11.17 2 18.79V19c0 4.42 3.58 8 8 8h12c4.42 0 8-3.58 8-8z");
}

.e87g1xiaj {
  stop-color: var(--svg-color--735a69, #735A69);
  stop-opacity: 0;
}

.eaxjz4ocb {
  stop-color: var(--svg-color--5e4755, #5E4755);
  stop-opacity: 0.25;
}

.eo7i18boh {
  stop-color: var(--svg-color--fc8bad, #FC8BAD);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h7chfx87x {
  d: path("M7.05 19.75a2.949 2.949 0 1 0 5.9 0v-3.88a2.949 2.949 0 1 0-5.9 0z");
}

.icxftsb3h {
  stop-color: var(--svg-color--fcbcc2, #FCBCC2);
}

.ipwj6sb4o {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.05 19.75a2.949 2.949 0 1 0 5.9 0v-3.88a2.949 2.949 0 1 0-5.9 0z");
}

.ji9st6dwc {
  d: path("M19.05 19.75a2.949 2.949 0 1 0 5.9 0v-3.88a2.949 2.949 0 1 0-5.9 0z");
}

.k3-y9hhvs {
  stop-color: var(--svg-color--423450, #423450);
}

.krzvm_bou {
  stop-color: var(--svg-color--1f1030, #1F1030);
}

.m-97rcbob {
  stop-color: var(--svg-color--f13f9e, #F13F9E);
  stop-opacity: 0;
}

.mydvbytws {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 .5h32v32H0z");
}

.q_w05_-5h {
  stop-color: var(--svg-color--ffc9d3, #FFC9D3);
  stop-opacity: 0;
}

.q5q095skb {
  stop-color: var(--svg-color--fc64a3, #FC64A3);
}

.s4i4zxnjz {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M19.05 19.75a2.949 2.949 0 1 0 5.9 0v-3.88a2.949 2.949 0 1 0-5.9 0z");
}

.t548e9bhn {
  stop-color: var(--svg-color--ffb1ba, #FFB1BA);
}

.t699csbqu {
  stop-color: var(--svg-color--e789ad, #E789AD);
}

.u0y0ggq7g {
  stop-color: var(--svg-color--ffc9d3, #FFC9D3);
}

.v7regbb_u {
  stop-color: var(--svg-color--735a69, #735A69);
}

.vk9p9db7a {
  fill-rule: evenodd;
  d: path("M29.281 20.813C29.625 11 23.11 7.063 15.5 7.063c10.563 1.218 13.428 9.412 13.781 13.75");
}

.w4y2v1bsw {
  stop-color: var(--svg-color--fcbcc2, #FCBCC2);
  stop-opacity: 0;
}

.xu5028djw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M10.647 21.313a1.995 1.995 0 0 1-1.996-1.997V15.22");
}

.z8tq47bnr {
  stop-color: var(--svg-color--f13f9e, #F13F9E);
}

.zves6ucjo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M22.397 21.313a1.995 1.995 0 0 1-1.996-1.997V15.22");
}

</style>

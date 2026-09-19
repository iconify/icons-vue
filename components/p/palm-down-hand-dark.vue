<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMIIm0t)" class="q5ph-n61m"/><path fill="url(#iyI7Aqc)" class="q5ph-n61m"/><path fill="url(#iesDF7b)" class="q5ph-n61m"/><path fill="url(#iobV1GO)" class="bxhgm4xpj"/><path fill="url(#iszOhhb)" class="bxhgm4xpj"/><path fill="url(#i0C61Oc)" class="bxhgm4xpj"/><path fill="url(#io0RDUd)" class="bxhgm4xpj"/><path fill="url(#iNABvPb)" class="avzk9jtjd"/><path fill="url(#izB2m6o)" class="avzk9jtjd"/><g filter="url(#iWSwshe)"><path fill="url(#i44nsMj)" class="gcgg-xxjc"/></g><path fill="url(#iAfrx5d)" class="gcgg-xxjc"/><g filter="url(#ia13UOd)"><path class="f799qd2rn"/></g><defs><radialGradient id="iMIIm0t" cx="0" cy="0" r="1" gradientTransform="matrix(1.1711 -3.78737 2.97467 .9198 15.244 16.91)" gradientUnits="userSpaceOnUse"><stop class="o7271kbnz"/><stop offset="1" class="zzkynkb_y"/></radialGradient><radialGradient id="iesDF7b" cx="0" cy="0" r="1" gradientTransform="matrix(.75744 4.71876 -3.97837 .6386 15.078 13.69)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="y9qrw4uop"/><stop offset=".909" class="sy5t-xw4w"/></radialGradient><radialGradient id="iobV1GO" cx="0" cy="0" r="1" gradientTransform="matrix(1 -7.625 2.64769 .34724 18.813 19.408)" gradientUnits="userSpaceOnUse"><stop class="jwu6ckbmd"/><stop offset="1" class="rd0gzhbxb"/></radialGradient><radialGradient id="iszOhhb" cx="0" cy="0" r="1" gradientTransform="matrix(-.81812 6.82953 -5.8375 -.69928 19.75 13.345)" gradientUnits="userSpaceOnUse"><stop offset=".86" class="w4a8dvb_l"/><stop offset=".965" class="t1zy-pbye"/></radialGradient><radialGradient id="i0C61Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 -7.375 7.2506 1.59758 18.313 20.47)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="r3yf3pzhg"/><stop offset="1" class="ae7vc0guh"/></radialGradient><radialGradient id="iNABvPb" cx="0" cy="0" r="1" gradientTransform="rotate(-104.097 19.995 .892)scale(7.18512 1.56176)" gradientUnits="userSpaceOnUse"><stop offset=".192" class="ng8lkmbuf"/><stop offset="1" class="t9e2icsnz"/></radialGradient><radialGradient id="izB2m6o" cx="0" cy="0" r="1" gradientTransform="matrix(-1.11676 7.14566 -4.4133 -.68973 24.188 13.564)" gradientUnits="userSpaceOnUse"><stop offset=".909" class="txoki8d3h"/><stop offset=".996" class="ftup562cz"/></radialGradient><radialGradient id="iAfrx5d" cx="0" cy="0" r="1" gradientTransform="matrix(5.75 6.5 -2.27067 2.00867 2.813 18.22)" gradientUnits="userSpaceOnUse"><stop class="ty4-qibqq"/><stop offset="1" class="sa8rgke9l"/></radialGradient><linearGradient id="iyI7Aqc" x1="17.138" x2="16.116" y1="17.608" y2="17.509" gradientUnits="userSpaceOnUse"><stop class="orxcgzb_c"/><stop offset="1" class="i1q72yb_z"/></linearGradient><linearGradient id="io0RDUd" x1="21.448" x2="20.128" y1="17.259" y2="17.509" gradientUnits="userSpaceOnUse"><stop class="l37_xy43p"/><stop offset="1" class="cfzdb-bml"/></linearGradient><linearGradient id="i44nsMj" x1="9.481" x2="26.71" y1="22.579" y2="10.485" gradientUnits="userSpaceOnUse"><stop class="o703jpb4x"/><stop offset="1" class="mhcyt_btx"/></linearGradient><filter id="iWSwshe" width="29.13" height="19.251" x="2.11" y="6.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.180392 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6744"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.231373 0 0 0 0 0.137255 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6744" result="effect2_innerShadow_20020_6744"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.32549 0 0 0 0 0.266667 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_20020_6744" result="effect3_innerShadow_20020_6744"/></filter><filter id="ia13UOd" width="27.142" height="18.811" x="3.296" y="6.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6744" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:palm-down-hand-dark" /></template>
<style>
.ae7vc0guh {
  stop-color: var(--svg-color--1c0a10, #1C0A10);
}

.avzk9jtjd {
  d: path("M23.929 20.672a2.19 2.19 0 0 1-2.552-1.753l-1.127-6.011l4.479.088l.953 5.124a2.193 2.193 0 0 1-1.753 2.552");
}

.bxhgm4xpj {
  d: path("M18.77 19.96a2.193 2.193 0 0 1-1.962-2.398l.52-5.185l4.357.436l-.52 5.185a2.186 2.186 0 0 1-2.395 1.962");
}

.cfzdb-bml {
  stop-color: var(--svg-color--1a0c0d, #1A0C0D);
  stop-opacity: 0;
}

.f799qd2rn {
  fill: var(--svg-color--624c4b, #624C4B);
  d: path("m21.423 9.556l6.69 5.27a.852.852 0 0 1-1.03 1.356l-6.163-4.516a2 2 0 0 0-1.424-.373l-4.98.607A4 4 0 0 0 11 15.87v.77a4 4 0 0 0 .961 2.601l.175.205a3 3 0 0 0 1.947 1.03l1.918.215a3 3 0 0 1 1.727.8l.846.797a.707.707 0 0 1-.939 1.058l-.437-.366a3 3 0 0 0-1.923-.697h-2.176a4 4 0 0 1-2.725-1.071l-3.803-3.538a4 4 0 0 1-1.17-3.835l.238-1.026a5 5 0 0 1 4.723-3.864l8.469-.249a4 4 0 0 1 2.592.856");
}

.ft5dv1b6b {
  fill: none;
}

.ftup562cz {
  stop-color: var(--svg-color--422844, #422844);
}

.gcgg-xxjc {
  d: path("M12.66 16.807c0-1.701.887-2.575 2.4-3.079c.976-.21 4.53-.148 4.53-.148c1.133 0 1.78.448 2.438 1.054l3.758 3.211c.984.907 2.484 1.119 3.492.078c1.053-1.085.937-2.734-.344-3.843L23.17 9.092c-1.3-1.169-1.922-1.817-4.31-1.817H9.887c-4.829-.03-7.777 2.93-7.777 6.805c0 2.344 2.082 4.807 3.683 6.468l1.72 1.634c1.36 1.207 3.132 2.226 4.976 2.226h1.828c.59 0 1.052-.059 1.789.383c.905.542 2.33.42 3.078-.329c.652-.651.85-1.587.504-2.444c-.601-1.497-2.262-2.126-3.879-2.438l-1.125-.157c-1.445-.101-2.023-1.734-2.023-2.616");
}

.i1q72yb_z {
  stop-color: var(--svg-color--1a0a0d, #1A0A0D);
  stop-opacity: 0;
}

.jwu6ckbmd {
  stop-color: var(--svg-color--453336, #453336);
}

.l37_xy43p {
  stop-color: var(--svg-color--1a0c0d, #1A0C0D);
}

.mhcyt_btx {
  stop-color: var(--svg-color--553b37, #553B37);
}

.ng8lkmbuf {
  stop-color: var(--svg-color--453135, #453135);
}

.o703jpb4x {
  stop-color: var(--svg-color--482d31, #482D31);
}

.o7271kbnz {
  stop-color: var(--svg-color--331c2a, #331C2A);
}

.orxcgzb_c {
  stop-color: var(--svg-color--1a0a0d, #1A0A0D);
}

.q5ph-n61m {
  d: path("M14.98 17.905a2.19 2.19 0 0 1-1.752-2.553l.947-5.12l4.305.799l-.95 5.121a2.186 2.186 0 0 1-2.55 1.753");
}

.r3yf3pzhg {
  stop-color: var(--svg-color--1c0a10, #1C0A10);
  stop-opacity: 0;
}

.rd0gzhbxb {
  stop-color: var(--svg-color--2e1b1c, #2E1B1C);
}

.sa8rgke9l {
  stop-color: var(--svg-color--4c3a3f, #4C3A3F);
  stop-opacity: 0;
}

.sy5t-xw4w {
  stop-color: var(--svg-color--3e243d, #3E243D);
}

.t1zy-pbye {
  stop-color: var(--svg-color--412742, #412742);
}

.t9e2icsnz {
  stop-color: var(--svg-color--382828, #382828);
}

.txoki8d3h {
  stop-color: var(--svg-color--422844, #422844);
  stop-opacity: 0;
}

.ty4-qibqq {
  stop-color: var(--svg-color--4c3a3f, #4C3A3F);
}

.w4a8dvb_l {
  stop-color: var(--svg-color--412742, #412742);
  stop-opacity: 0;
}

.y9qrw4uop {
  stop-color: var(--svg-color--3e243d, #3E243D);
  stop-opacity: 0;
}

.zzkynkb_y {
  stop-color: var(--svg-color--1b0b0f, #1B0B0F);
}

</style>

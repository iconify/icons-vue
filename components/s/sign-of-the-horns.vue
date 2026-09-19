<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iv8JXAc)"><path class="xzl92pbwy"/></g><g filter="url(#i5XQfod)" class="guba0gt7f"><path class="pfe1pacnp"/></g><g filter="url(#iqdvoje)"><path fill="url(#iHufqgn)" class="ktd5xrbtc"/></g><rect fill="url(#i6oLKTd)" class="rnw81cc0v"/><rect fill="url(#ili9vJt)" class="rnw81cc0v"/><rect fill="url(#iaUkDld)" class="k9xaoqqep"/><g filter="url(#i7s7lla)"><rect fill="url(#iVNLONZ)" class="o74wf0bdl"/><rect fill="url(#iu5NTsd)" class="o74wf0bdl"/></g><rect fill="url(#iDcS4zd)" class="o74wf0bdl"/><rect fill="url(#ip9HNOc)" class="o74wf0bdl"/><g filter="url(#i8AUHkd)"><rect fill="url(#iXPtnsd)" class="ihvytccoe"/></g><rect fill="url(#iYHfVoc)" class="ihvytccoe"/><g filter="url(#iok89Le)"><path class="h2nd12b4l"/></g><path fill="url(#iJjrXWd)" class="anmos7bcy"/><path fill="url(#iU5n7ad)" class="anmos7bcy"/><path fill="url(#iJjrXWd)" class="hkklrdbbe"/><path fill="url(#iU5n7ad)" class="hkklrdbbe"/><g filter="url(#i5ZAR2c)"><path stroke="url(#iffMhKl)" class="ippn3db9l"/></g><path fill="url(#iz3LtZd)" class="q9j8zzbkm"/><path fill="url(#iTvbM8b)" class="q9j8zzbkm"/><defs><linearGradient id="iHufqgn" x1="11.264" x2="15.237" y1="14.456" y2="16.299" gradientUnits="userSpaceOnUse"><stop class="vbh9d9bpt"/><stop offset="1" class="zw0xkobnj"/></linearGradient><linearGradient id="iVNLONZ" x1="11.915" x2="14.864" y1="11.438" y2="11.56" gradientUnits="userSpaceOnUse"><stop class="p-6zavbqs"/><stop offset="1" class="rxiiszonf"/></linearGradient><linearGradient id="ip9HNOc" x1="15.398" x2="15.028" y1="12.906" y2="12.906" gradientUnits="userSpaceOnUse"><stop class="ge-fh-b1p"/><stop offset="1" class="c6cr2ztby"/></linearGradient><linearGradient id="iXPtnsd" x1="16.302" x2="20.739" y1="10.638" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="p-6zavbqs"/><stop offset="1" class="rxiiszonf"/></linearGradient><linearGradient id="iYHfVoc" x1="21.21" x2="18.073" y1="11.495" y2="11.495" gradientUnits="userSpaceOnUse"><stop class="pcwt4rb7z"/><stop offset="1" class="ooih2wkqf"/></linearGradient><linearGradient id="iU5n7ad" x1="24.642" x2="21.636" y1="22.688" y2="20.179" gradientUnits="userSpaceOnUse"><stop offset=".249" class="l6wm2hbma"/><stop offset="1" class="esv-4bbmx"/></linearGradient><linearGradient id="iffMhKl" x1="17.641" x2="24.987" y1="16.18" y2="18.892" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tt62452ik"/></linearGradient><linearGradient id="iz3LtZd" x1="26.12" x2="23.557" y1="16.723" y2="16.723" gradientUnits="userSpaceOnUse"><stop class="hhhmpg_tl"/><stop offset="1" class="t_6gebccb"/></linearGradient><radialGradient id="i6oLKTd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.39062 3.59376 -2.77814 -2.6211 12.745 12.664)" gradientUnits="userSpaceOnUse"><stop class="vuxosrrll"/><stop offset="1" class="nsjf-owkq"/></radialGradient><radialGradient id="ili9vJt" cx="0" cy="0" r="1" gradientTransform="rotate(133.254 4.196 5.73)scale(3.51834 3.48985)" gradientUnits="userSpaceOnUse"><stop class="u44n60b3i"/><stop offset="1" class="ape2p8bnd"/></radialGradient><radialGradient id="iaUkDld" cx="0" cy="0" r="1" gradientTransform="matrix(-2.07884 4.00058 -3.76893 -1.95847 24.84 2.602)" gradientUnits="userSpaceOnUse"><stop class="u44n60b3i"/><stop offset="1" class="ape2p8bnd"/></radialGradient><radialGradient id="iu5NTsd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31357 .85703 -1.14666 -1.7575 16.282 9.946)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="u0230sz1k"/><stop offset="1" class="cp7yf0bpk"/></radialGradient><radialGradient id="iDcS4zd" cx="0" cy="0" r="1" gradientTransform="rotate(-129.818 12.024 4.933)scale(4.21217 2.77)" gradientUnits="userSpaceOnUse"><stop class="g22kozbsd"/><stop offset="1" class="jwejy4wqy"/></radialGradient><radialGradient id="iJjrXWd" cx="0" cy="0" r="1" gradientTransform="rotate(112.817 6.055 15.188)scale(5.35728 16.4557)" gradientUnits="userSpaceOnUse"><stop class="hkmq-95fz"/><stop offset="1" class="n28w0ofig"/></radialGradient><radialGradient id="iTvbM8b" cx="0" cy="0" r="1" gradientTransform="matrix(22.82617 10.50104 -11.16142 24.26165 3.886 11.694)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="t_6gebccb"/><stop offset="1" class="hhhmpg_tl"/></radialGradient><filter id="iv8JXAc" width="20.413" height="28.703" x="6.169" y="1.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.490196 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2478"/></filter><filter id="i5XQfod" width="14.875" height="9.703" x="11.52" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2478" stdDeviation="1"/></filter><filter id="iqdvoje" width="10.099" height="10.995" x="7.835" y="8.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2478" stdDeviation="1"/></filter><filter id="i7s7lla" width="6.145" height="8.953" x="10.54" y="8.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.533333 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2478"/></filter><filter id="i8AUHkd" width="6.082" height="11.031" x="15.407" y="6.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.921569 0 0 0 0 0.533333 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2478"/></filter><filter id="iok89Le" width="5.5" height="19.063" x="20.777" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2478" stdDeviation="1"/></filter><filter id="i5ZAR2c" width="12.754" height="9.846" x="14.641" y="13.181" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2478" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sign-of-the-horns" /></template>
<style>
.anmos7bcy {
  d: path("M17.739 14.117a2.852 2.852 0 0 0 0 5.703h1.624a1 1 0 0 1 .743.441l2.471 3.652a1 1 0 0 0 1.745-.16l.937-2.142c.332-.759.543-1.586.38-2.398a6.346 6.346 0 0 0-6.213-5.096");
}

.ape2p8bnd {
  stop-color: var(--svg-color--ffe243, #FFE243);
  stop-opacity: 0;
}

.c6cr2ztby {
  stop-color: var(--svg-color--c57503, #C57503);
  stop-opacity: 0;
}

.cp7yf0bpk {
  stop-color: var(--svg-color--ad690c, #AD690C);
  stop-opacity: 0;
}

.esv-4bbmx {
  stop-color: var(--svg-color--ffaf42, #FFAF42);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g22kozbsd {
  stop-color: var(--svg-color--d76d21, #D76D21);
}

.ge-fh-b1p {
  stop-color: var(--svg-color--c57503, #C57503);
}

.guba0gt7f {
  fill: var(--svg-color--d37223, #D37223);
}

.h2nd12b4l {
  stroke: var(--svg-color--ffe446, #FFE446);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M23.527 4.602v13.562");
}

.hhhmpg_tl {
  stop-color: var(--svg-color--ffdd40, #FFDD40);
}

.hkklrdbbe {
  d: path("M17.739 14.117h1.68Z");
}

.hkmq-95fz {
  stop-color: var(--svg-color--ffe54a, #FFE54A);
}

.ihvytccoe {
  width: 5.332px;
  height: 10.281px;
  x: 15.407px;
  y: 7.195px;
  rx: 2.666px;
}

.ippn3db9l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.64 16.18h2.285a3 3 0 0 1 2.363 1.152l2.107 2.694");
}

.jwejy4wqy {
  stop-color: var(--svg-color--d76d21, #D76D21);
  stop-opacity: 0;
}

.k9xaoqqep {
  width: 5.332px;
  height: 15.453px;
  x: 20.094px;
  y: 2.023px;
  rx: 2.666px;
}

.ktd5xrbtc {
  d: path("M9.835 10.959h6.099v6.995H9.835z");
}

.l6wm2hbma {
  stop-color: var(--svg-color--ffaf42, #FFAF42);
}

.n28w0ofig {
  stop-color: var(--svg-color--ed7f37, #ED7F37);
}

.nsjf-owkq {
  stop-color: var(--svg-color--d25a17, #D25A17);
  stop-opacity: 0;
}

.o74wf0bdl {
  width: 5.395px;
  height: 8.203px;
  x: 10.54px;
  y: 8.805px;
  rx: 2.697px;
}

.ooih2wkqf {
  stop-color: var(--svg-color--ffe33f, #FFE33F);
  stop-opacity: 0;
}

.p-6zavbqs {
  stop-color: var(--svg-color--fabb25, #FABB25);
}

.pcwt4rb7z {
  stop-color: var(--svg-color--ffe33f, #FFE33F);
}

.pfe1pacnp {
  d: path("M16.372 15.252a2.852 2.852 0 0 0 0 5.703h1.624c3.034 0 4.127 0 6.399-.256c0-3.5-2.836-5.443-6.336-5.447m-1.687 0h1.68Z");
}

.q9j8zzbkm {
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v3.434c.402.467.645 1.074.645 1.738v4.95a2.666 2.666 0 0 1-5.184.879a2.697 2.697 0 0 1-5.016-1.38v-2.808c0-.828.374-1.57.962-2.064V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.rnw81cc0v {
  width: 5.332px;
  height: 11.813px;
  x: 6.169px;
  y: 5.664px;
  rx: 2.666px;
}

.rxiiszonf {
  stop-color: var(--svg-color--ffd43e, #FFD43E);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.t_6gebccb {
  stop-color: var(--svg-color--ffdd40, #FFDD40);
  stop-opacity: 0;
}

.tt62452ik {
  stop-color: var(--svg-color--ffe446, #FFE446);
  stop-opacity: 0;
}

.u0230sz1k {
  stop-color: var(--svg-color--ad690c, #AD690C);
}

.u44n60b3i {
  stop-color: var(--svg-color--ffe243, #FFE243);
}

.vbh9d9bpt {
  stop-color: var(--svg-color--d37223, #D37223);
}

.vuxosrrll {
  stop-color: var(--svg-color--d25a17, #D25A17);
}

.xzl92pbwy {
  fill: var(--svg-color--ffaf42, #FFAF42);
  d: path("M22.76 2.023a2.666 2.666 0 0 0-2.666 2.666v8.217h-8.593V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a95 95 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.zw0xkobnj {
  stop-color: var(--svg-color--b84a10, #B84A10);
}

</style>

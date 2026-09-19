<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="qpsdt0zmu"/><path fill="url(#i7KQbub)" class="flq3nbb8o"/><path fill="url(#il0cu6d)" class="flq3nbb8o"/><path fill="url(#iipUkld)" class="flq3nbb8o"/><path fill="url(#im914Zc)" class="flq3nbb8o"/><g filter="url(#iKi3GOb)"><path class="t-ugwt3fg"/><path fill="url(#ij1WEJe)" class="zuxhdrb3z"/><path fill="url(#ikiE4jb)" class="zuxhdrb3z"/><path fill="url(#iHUmH2c)" class="zuxhdrb3z"/><path fill="url(#idNGZYc)" class="zuxhdrb3z"/><path fill="url(#i2xJQ3q)" class="zuxhdrb3z"/></g><path fill="url(#ifkGmiJ)" class="s19yjkp9b"/><path fill="url(#iBRwUre)" class="s19yjkp9b"/><path fill="url(#i7PXDtb)" class="s19yjkp9b"/><path fill="url(#iOw1SyY)" class="udviifhky"/><path fill="url(#iXlN6Wd)" class="udviifhky"/><path fill="url(#igtNM4c)" class="udviifhky"/><g filter="url(#ikcDADb)"><path stroke="url(#im30brb)" class="ltqgp4bmv"/></g><g filter="url(#iC1FQpd)"><path stroke="url(#iNVINJb)" class="nruxfdbuf"/></g><path fill="url(#icHs0ly)" class="zuxhdrb3z"/><path fill="url(#iBuBD9c)" class="zuxhdrb3z"/><defs><radialGradient id="i7KQbub" cx="0" cy="0" r="1" gradientTransform="matrix(3.32781 -.20824 .28278 4.51907 20.57 3.593)" gradientUnits="userSpaceOnUse"><stop class="t9pqx54ml"/><stop offset="1" class="lq40rxikh"/></radialGradient><radialGradient id="il0cu6d" cx="0" cy="0" r="1" gradientTransform="rotate(-32.25 29.657 -37.222)scale(4.48566 10.4433)" gradientUnits="userSpaceOnUse"><stop class="t9pqx54ml"/><stop offset="1" class="lq40rxikh"/></radialGradient><radialGradient id="iipUkld" cx="0" cy="0" r="1" gradientTransform="rotate(-65.731 31.556 -9.639)scale(8.57053 2.66744)" gradientUnits="userSpaceOnUse"><stop class="t9pqx54ml"/><stop offset="1" class="lq40rxikh"/></radialGradient><radialGradient id="im914Zc" cx="0" cy="0" r="1" gradientTransform="matrix(-11.375 -15.87497 8.3679 -5.9959 32.148 17.12)" gradientUnits="userSpaceOnUse"><stop offset=".914" class="lq40rxikh"/><stop offset="1" class="t9pqx54ml"/></radialGradient><radialGradient id="ij1WEJe" cx="0" cy="0" r="1" gradientTransform="rotate(-23.656 59.029 10.748)scale(30.9972 29.5828)" gradientUnits="userSpaceOnUse"><stop offset=".869" class="m793l5bdm"/><stop offset="1" class="qkblpbbna"/></radialGradient><radialGradient id="ikiE4jb" cx="0" cy="0" r="1" gradientTransform="matrix(10.414 0 0 5.43789 3.21 23.355)" gradientUnits="userSpaceOnUse"><stop class="xoe6srzbk"/><stop offset="1" class="ahau3zszh"/></radialGradient><radialGradient id="iHUmH2c" cx="0" cy="0" r="1" gradientTransform="matrix(2.05479 3.5407 -3.62102 2.1014 9.98 16.265)" gradientUnits="userSpaceOnUse"><stop class="fauif0b3f"/><stop offset="1" class="gtrt1jbfc"/></radialGradient><radialGradient id="idNGZYc" cx="0" cy="0" r="1" gradientTransform="rotate(120.056 5.886 14.694)scale(6.52613 4.58823)" gradientUnits="userSpaceOnUse"><stop offset=".491" class="u7puw9nce"/><stop offset="1" class="f_12r6bzq"/></radialGradient><radialGradient id="i2xJQ3q" cx="0" cy="0" r="1" gradientTransform="matrix(-2.42065 4.92201 -4.03635 -1.98508 21.546 17.17)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="wzo_j5o5v"/><stop offset="1" class="rd0rpmpsg"/></radialGradient><radialGradient id="ifkGmiJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.75998 1.43553 -2.195 -1.16205 21.296 8.108)" gradientUnits="userSpaceOnUse"><stop class="msz2nkx7f"/><stop offset="1" class="sb7dl_nwc"/></radialGradient><radialGradient id="iBRwUre" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.28125 -2.84207 -.15573 19.382 5.39)" gradientUnits="userSpaceOnUse"><stop class="cx-rls3zr"/><stop offset="1" class="llr5c1bnb"/></radialGradient><radialGradient id="iOw1SyY" cx="0" cy="0" r="1" gradientTransform="matrix(3.77932 1.1332 -1.36518 4.55298 21.601 14.181)" gradientUnits="userSpaceOnUse"><stop class="ofcsa759z"/><stop offset="1" class="cpuf2vxig"/></radialGradient><radialGradient id="iXlN6Wd" cx="0" cy="0" r="1" gradientTransform="matrix(3.52645 -.84408 1.07229 4.47988 20.581 9.765)" gradientUnits="userSpaceOnUse"><stop offset=".457" class="mxyh7fbey"/><stop offset="1" class="h7zqzdi4d"/></radialGradient><radialGradient id="igtNM4c" cx="0" cy="0" r="1" gradientTransform="rotate(13.65 -10.836 80.38)scale(4.50217 3.60618)" gradientUnits="userSpaceOnUse"><stop class="qvsikogbe"/><stop offset="1" class="bzxx78b8p"/></radialGradient><linearGradient id="i7PXDtb" x1="15.242" x2="17.496" y1="9.437" y2="10.978" gradientUnits="userSpaceOnUse"><stop class="r2ba16i9a"/><stop offset="1" class="mwfrkwb9e"/></linearGradient><linearGradient id="im30brb" x1="27.867" x2="25.499" y1="15.696" y2="25.776" gradientUnits="userSpaceOnUse"><stop class="pts0xy57c"/><stop offset="1" class="twwcrgbem"/></linearGradient><linearGradient id="iNVINJb" x1="21.431" x2="21.101" y1="8.627" y2="15.722" gradientUnits="userSpaceOnUse"><stop class="ag47qzb-q"/><stop offset="1" class="hodgx345b"/></linearGradient><linearGradient id="icHs0ly" x1="8.384" x2="8.384" y1="35.619" y2="23.433" gradientUnits="userSpaceOnUse"><stop class="omitdb1eb"/><stop offset="1" class="npqbdbcfh"/></linearGradient><linearGradient id="iBuBD9c" x1="3.116" x2="3.941" y1="24.004" y2="24.004" gradientUnits="userSpaceOnUse"><stop class="fwis2tb9u"/><stop offset="1" class="x3b47vblu"/></linearGradient><filter id="iKi3GOb" width="26.58" height="27.521" x="2.96" y="2.005" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.368627 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1900"/></filter><filter id="ikcDADb" width="11.961" height="16.255" x="17.894" y="9.274" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1900" stdDeviation=".75"/></filter><filter id="iC1FQpd" width="7.832" height="10.645" x="14.581" y="7.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1900" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinched-fingers-medium" /></template>
<style>
.ag47qzb-q {
  stop-color: var(--svg-color--d2a98e, #D2A98E);
}

.ahau3zszh {
  stop-color: var(--svg-color--b38974, #B38974);
  stop-opacity: 0;
}

.bzxx78b8p {
  stop-color: var(--svg-color--8d725f, #8D725F);
  stop-opacity: 0;
}

.cpuf2vxig {
  stop-color: var(--svg-color--8a6959, #8A6959);
  stop-opacity: 0;
}

.cx-rls3zr {
  stop-color: var(--svg-color--a18773, #A18773);
}

.f_12r6bzq {
  stop-color: var(--svg-color--cea38a, #CEA38A);
  stop-opacity: 0;
}

.fauif0b3f {
  stop-color: var(--svg-color--8d7361, #8D7361);
}

.flq3nbb8o {
  d: path("M24.2 1.926c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.ft5dv1b6b {
  fill: none;
}

.fwis2tb9u {
  stop-color: var(--svg-color--956c60, #956C60);
}

.gtrt1jbfc {
  stop-color: var(--svg-color--8d7361, #8D7361);
  stop-opacity: 0;
}

.h7zqzdi4d {
  stop-color: var(--svg-color--7e4e4c, #7E4E4C);
  stop-opacity: 0;
}

.hodgx345b {
  stop-color: var(--svg-color--d2a98e, #D2A98E);
  stop-opacity: 0;
}

.llr5c1bnb {
  stop-color: var(--svg-color--a18773, #A18773);
  stop-opacity: 0;
}

.lq40rxikh {
  stop-color: var(--svg-color--8b6c57, #8B6C57);
  stop-opacity: 0;
}

.ltqgp4bmv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M27.306 11.774c.514 4.95-3.035 10.087-6.911 11.254");
}

.m793l5bdm {
  stop-color: var(--svg-color--c6a183, #C6A183);
  stop-opacity: 0;
}

.msz2nkx7f {
  stop-color: var(--svg-color--cea58f, #CEA58F);
}

.mwfrkwb9e {
  stop-color: var(--svg-color--a17975, #A17975);
  stop-opacity: 0;
}

.mxyh7fbey {
  stop-color: var(--svg-color--7e4e4c, #7E4E4C);
}

.npqbdbcfh {
  stop-color: var(--svg-color--985884, #985884);
  stop-opacity: 0;
}

.nruxfdbuf {
  stroke-linecap: round;
  d: path("M20.413 9.355L16.58 16");
}

.ofcsa759z {
  stop-color: var(--svg-color--8a6959, #8A6959);
}

.omitdb1eb {
  stop-color: var(--svg-color--985884, #985884);
}

.pts0xy57c {
  stop-color: var(--svg-color--d1a98e, #D1A98E);
}

.qkblpbbna {
  stop-color: var(--svg-color--c6a183, #C6A183);
}

.qpsdt0zmu {
  fill: var(--svg-color--cca486, #CCA486);
  d: path("M24.2 1.926c-.42-.25-.9-.4-1.42-.4a2.659 2.659 0 0 0-1.08 5.09c.35.3.89.79 1.41 1.47c1.09 1.4 1.64 2.93 1.64 4.52c0 2.31-1.18 4.21-2.18 5.39c-1.43 1.7-3.12 2.7-4.12 3.04a2.625 2.625 0 0 0 .84 5.11c.28 0 .56-.04.84-.14c2.24-.75 4.66-2.49 6.47-4.64c1.56-1.85 3.41-4.87 3.41-8.77c-.02-6.77-5.58-10.52-5.81-10.67");
}

.qvsikogbe {
  stop-color: var(--svg-color--8d725f, #8D725F);
}

.r2ba16i9a {
  stop-color: var(--svg-color--a17975, #A17975);
}

.rd0rpmpsg {
  stop-color: var(--svg-color--b18e75, #B18E75);
  stop-opacity: 0;
}

.s19yjkp9b {
  d: path("M17.17 7.369a2.886 2.886 0 0 1 4.995 2.892l-4.314 7.718c-.799 1.38-2.557 1.573-3.937.775c-1.38-.799-1.897-2.517-1.098-3.896z");
}

.sb7dl_nwc {
  stop-color: var(--svg-color--cea58f, #CEA58F);
  stop-opacity: 0;
}

.t-ugwt3fg {
  fill: var(--svg-color--bc8b81, #BC8B81);
  d: path("M23.25 3.406c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3.96c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

.t9pqx54ml {
  stop-color: var(--svg-color--8b6c57, #8B6C57);
}

.twwcrgbem {
  stop-color: var(--svg-color--d1a98e, #D1A98E);
  stop-opacity: 0;
}

.u7puw9nce {
  stop-color: var(--svg-color--cea38a, #CEA38A);
}

.udviifhky {
  d: path("M29.04 14.086a12.4 12.4 0 0 1-.566 3.69l-5.608 6.03l-2.562-6.03l-.017-.044q.051.003.103.004c1.76 0 3.24-1.34 3.38-3.09l.001-.028c.01-.18.019-.351.019-.532c0-1.493-.475-2.916-1.426-4.24a2.89 2.89 0 0 0-1.25-3.53c-.67-.387-1.263-.415-1.924-.35l-.001-.014a2.682 2.682 0 0 1 2.731-2.946c.48.02.94.16 1.33.4c.24.16 5.8 3.91 5.79 10.68");
}

.wzo_j5o5v {
  stop-color: var(--svg-color--8a6754, #8A6754);
}

.x3b47vblu {
  stop-color: var(--svg-color--956c60, #956C60);
  stop-opacity: 0;
}

.xoe6srzbk {
  stop-color: var(--svg-color--b38974, #B38974);
}

.zuxhdrb3z {
  d: path("M23.25 3.406c-.39-.24-.85-.38-1.33-.4a2.68 2.68 0 0 0-2.74 2.52c-.01.15 0 .29.01.44c-.84.14-1.6.64-2.04 1.44l-5.32 9.15c-.7 1.22-2 1.97-3.41 1.97H3.96c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h7.58c3.72 0 7.37-1.12 10.4-3.28c.64-.45 1.27-.97 1.88-1.55c.64-.56 1.25-1.18 1.81-1.84c1.56-1.85 3.41-4.87 3.41-8.77c.01-6.77-5.55-10.52-5.79-10.68m-4.26 12.92c0-.24.06-.47.18-.68l3.01-5.45c.07-.12.12-.25.17-.37c.96 1.33 1.44 2.76 1.44 4.26c0 .19-.01.37-.02.56c-.14 1.75-1.62 3.09-3.38 3.09c-.77 0-1.4-.63-1.4-1.41");
}

</style>

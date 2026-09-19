<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i5F1Btx)" class="h3iabd7xc"/><path fill="url(#iYNhumd)" class="h3iabd7xc"/><path fill="url(#igshAij)" class="h3iabd7xc"/><path fill="url(#iwU4CLp)" class="h3iabd7xc"/><path fill="url(#i5huQWg)" class="h3iabd7xc"/><defs><radialGradient id="i5F1Btx" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 9.965 9.872)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="xfuv6yisx"/><stop offset=".959" class="h25dgj-iw"/></radialGradient><radialGradient id="igshAij" cx="0" cy="0" r="1" gradientTransform="rotate(136.38 10.092 10.202)scale(14.6767 15.816)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="u3brf-1wi"/><stop offset="1" class="gkxsho4-e"/></radialGradient><radialGradient id="iwU4CLp" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.249 15.875)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="axntoaczi"/><stop offset=".951" class="c9hru3c5o"/></radialGradient><radialGradient id="i5huQWg" cx="0" cy="0" r="1" gradientTransform="scale(23.3208 21)rotate(90 .127 .55)" gradientUnits="userSpaceOnUse"><stop offset=".792" class="r976-down"/><stop offset="1" class="fspni_b1j"/></radialGradient><linearGradient id="iYNhumd" x1="15.757" x2="15.757" y1="1.875" y2="8.375" gradientUnits="userSpaceOnUse"><stop class="p47znkbkg"/><stop offset="1" class="r34926buv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:yellow-circle" /></template>
<style>
.axntoaczi {
  stop-color: var(--svg-color--c69b40, #C69B40);
  stop-opacity: 0;
}

.c9hru3c5o {
  stop-color: var(--svg-color--e8c290, #E8C290);
}

.fspni_b1j {
  stop-color: var(--svg-color--d17887, #D17887);
}

.ft5dv1b6b {
  fill: none;
}

.gkxsho4-e {
  stop-color: var(--svg-color--f8ca4d, #F8CA4D);
  stop-opacity: 0;
}

.h25dgj-iw {
  stop-color: var(--svg-color--c79738, #C79738);
}

.h3iabd7xc {
  d: path("M29.757 15.875c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.p47znkbkg {
  stop-color: var(--svg-color--e1b45d, #E1B45D);
}

.r34926buv {
  stop-color: var(--svg-color--e1b45d, #E1B45D);
  stop-opacity: 0;
}

.r976-down {
  stop-color: var(--svg-color--e5a152, #E5A152);
  stop-opacity: 0;
}

.u3brf-1wi {
  stop-color: var(--svg-color--ffe764, #FFE764);
}

.xfuv6yisx {
  stop-color: var(--svg-color--f3bb4b, #F3BB4B);
}

</style>

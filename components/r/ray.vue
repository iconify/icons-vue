<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGH4pFLejp)" class="kl54ovhhm"/><path fill="url(#SVGK1CYFbIe)" class="d0wzcwb4h"/><path fill="url(#SVGf5lVbefX)" class="d74qc3bkp"/><path fill="url(#SVGd7gfmeXu)" class="p8rk3iymz"/><defs><linearGradient id="SVGH4pFLejp" x1="19.986" x2="3.145" y1="7.506" y2="14.418" gradientUnits="userSpaceOnUse"><stop class="f314_iu6t"/><stop offset=".49" class="vwzpv59ae"/><stop offset="1" class="upr4icqsm"/></linearGradient><linearGradient id="SVGK1CYFbIe" x1="31.042" x2="-9.269" y1="1.888" y2="19.986" gradientUnits="userSpaceOnUse"><stop class="f314_iu6t"/><stop offset=".49" class="vwzpv59ae"/><stop offset="1" class="upr4icqsm"/></linearGradient><linearGradient id="SVGf5lVbefX" x1="43.977" x2="-58.386" y1="-44.916" y2="-14.224" gradientUnits="userSpaceOnUse"><stop class="f314_iu6t"/><stop offset=".49" class="vwzpv59ae"/><stop offset="1" class="upr4icqsm"/></linearGradient><linearGradient id="SVGd7gfmeXu" x1="20.003" x2="2.109" y1="7.504" y2="14.733" gradientUnits="userSpaceOnUse"><stop class="f314_iu6t"/><stop offset=".49" class="vwzpv59ae"/><stop offset="1" class="upr4icqsm"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ray" /></template>
<style>
.d0wzcwb4h {
  d: path("M10.5 16H9v-4h3.5c.76-.008 1.498-.508 1.5-1.28c.008-.758-.748-1.225-1.5-1.22H9V8h3.794c1.602 0 2.693 1.2 2.705 2.72c.014 1.642-1.286 2.78-3.108 2.78h-1.892z");
}

.d74qc3bkp {
  d: path("M15.757 16h-1.743l-1.079-1.896c.427-.025 1.16-.2 1.574-.424z");
}

.f314_iu6t {
  stop-color: var(--svg-color--c200fb, #c200fb);
}

.ft5dv1b6b {
  fill: none;
}

.kl54ovhhm {
  d: path("M19 10v6l-7 3.88L5 16V8l7-3.894l5.506 2.928l.832-.468L12 3L4 7.501v8.998L12 21l8-4.501V9.288z");
}

.p8rk3iymz {
  d: path("m18.25 8.52l.875.48l.875-.48V7.501L19.125 7l-.875.502z");
}

.upr4icqsm {
  stop-color: var(--svg-color--5ac4be, #5ac4be);
}

.vwzpv59ae {
  stop-color: var(--svg-color--3773fe, #3773fe);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kpn0pcbtz"/><path class="ga5w-99vs"/><path class="plx4y6zts"/><path class="wvr-g8bhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:signal-flag-sharp" /></template>
<style>
.ga5w-99vs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.48 4.04l3.04.92l.48.14v5.4H4V3.9z");
}

.kpn0pcbtz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25c5.75 3 12.75 3 18.5 0");
}

.plx4y6zts {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wvr-g8bhm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 5.6h2.5l-.13.48l-1.24 4.44L12 11l-.13-.48l-1.24-4.44l-.13-.48zm5.48-.64l3.04-.92l.48-.14v6.6h-4V5.1zM17 9.25l2-3");
}

</style>

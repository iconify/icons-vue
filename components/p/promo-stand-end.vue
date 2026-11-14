<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2q6frbai"/><path class="b5bdgxd5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:promo-stand-end" /></template>
<style>
.b5bdgxd5t {
  d: path("M5.5 5za.92.92 0 0 0 1.193.877l.807-.252a.655.655 0 0 0 0-1.25l-.807-.252A.92.92 0 0 0 5.5 5M11 5h7M4.5 14.5h15M7 14.5v-3l1-1v-1m2 0v1l1 1v3m4-4h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5m-6.5 7h1A1.5 1.5 0 0 1 11 19v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 7 20v-1a1.5 1.5 0 0 1 1.5-1.5m6 .5h2a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 13 20v-.5a1.5 1.5 0 0 1 1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2q6frbai {
  d: path("M4.75 2.5h14.5A1.75 1.75 0 0 1 21 4.25v1.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 5.75v-1.5A1.75 1.75 0 0 1 4.75 2.5m-.25 5v14m15-14v14m-17 0h19");
}

</style>

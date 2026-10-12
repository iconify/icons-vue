<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="necu--btd"/><path class="dvhbmjbrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mountain-flag" /></template>
<style>
.dvhbmjbrm {
  d: path("m8.5 16.75l1.25-1l1.25 1l1.25-1l1.25 1M10 9.4V6.25m.47-3.34l4.31 1.43q.47.16 0 .32l-4.31 1.43q-.47.16-.47-.34v-2.5q0-.5.47-.34");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.necu--btd {
  d: path("M3.28 19.9L9.47 9.85Q10 9 10.6 9.8l1.8 2.4q.6.8 1.23.03l.99-1.21q.63-.77 1.13.1l5 8.76q.5.87-.5.87H3.75q-1 0-.47-.85");
}

</style>

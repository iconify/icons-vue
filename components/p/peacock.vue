<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="j7aj8zrpi"/><path class="s8djojbdf"/><path class="zlj2jdbxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:peacock" /></template>
<style>
.j7aj8zrpi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.31 18.2a1.75 1.25-172 1 0-3.47-.49a1.75 1.25-172 1 0 3.47.49m1.38-4.72a1.75 1.25-128 1 0-2.15-2.75a1.75 1.25-128 1 0 2.15 2.75m8.62 0a1.75 1.25-52 1 0 2.15-2.75a1.75 1.25-52 1 0-2.15 2.75m1.38 4.72a1.75 1.25-8 1 0 3.47-.49a1.75 1.25-8 1 0-3.47.49m-8.15.45l-3.23-.45m4.36-.9l-2.98-3.82m5.64 3.82l2.98-3.82m-1.85 5.17l3.23-.45M12 6.25a1.75 1.25-90 1 0 0-3.5a1.75 1.25-90 1 0 0 3.5M9.5 19a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0m2.5-2v-4.5");
}

.s8djojbdf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 11.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m.55-1.05L9.75 8.5m2.95 1.7l1.55-1.7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zlj2jdbxa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 8.5h.01M12 7.9h.01m2.24.6h.01");
}

</style>

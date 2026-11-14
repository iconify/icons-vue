<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3sm54b4a"/><path class="km2rl3bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:peony" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.km2rl3bol {
  d: path("M12 9.5a1.25 1.25 0 0 1 2.5 0a2.5 2.5 0 0 1-5 0M12 21c1-1.5 3-2 5.5-1.75c-1 1.75-3 2.25-5.5 1.75");
}

.t3sm54b4a {
  d: path("M12 2.5A4.5 4.5 0 0 1 18 6a4.5 4.5 0 0 1 0 7a4.5 4.5 0 0 1-6 3.5A4.5 4.5 0 0 1 6 13a4.5 4.5 0 0 1 0-7a4.5 4.5 0 0 1 6-3.5m0 14v5");
}

</style>

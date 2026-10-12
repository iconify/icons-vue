<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="blp_zbb6h"/><path class="lrfmhcckg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep-mask" /></template>
<style>
.blp_zbb6h {
  d: path("M15.75 2.75h3.5l-3.5 3.5h3.5M2.75 12c0-2 1.5-3.5 3.75-3.5h11c2.25 0 3.75 1.5 3.75 3.5v.5c0 3-2.1 5-4.75 5c-2 0-3.1-1.5-4.5-1.5s-2.5 1.5-4.5 1.5c-2.65 0-4.75-2-4.75-5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lrfmhcckg {
  d: path("M5.75 12.5c1.1.9 2.65.9 3.75 0m5 0c1.1.9 2.65.9 3.75 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydspy9efb"/><path class="gfqf2i9ax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seed-sack" /></template>
<style>
.gfqf2i9ax {
  d: path("M12 12.5c1.75 1.25 1.75 4.25 0 5.5c-1.75-1.25-1.75-4.25 0-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydspy9efb {
  d: path("M8.75 7.75C5.75 10 3.5 13 3.5 16.25c0 3 2 5 5 5h7c3 0 5-2 5-5c0-3.25-2.25-6.25-5.25-8.5Zm.25 0L7.25 3.5c1.5.5 3 .75 4.75.75s3.25-.25 4.75-.75L15 7.75Z");
}

</style>

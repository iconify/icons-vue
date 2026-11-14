<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dvri9vb8t"/><path class="umpb_i87q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleeping-bag-liner" /></template>
<style>
.dvri9vb8t {
  d: path("M12 2.5c4 0 5.5 2.5 5.5 5.5c0 5-1.5 9-2.5 13.5H9C8 17 6.5 13 6.5 8C6.5 5 8 2.5 12 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umpb_i87q {
  d: path("M9.5 7a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0m0 4.75c0 2.75 1 5.25 1.75 7h1.5c.75-1.75 1.75-4.25 1.75-7");
}

</style>

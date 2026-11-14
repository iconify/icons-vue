<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn0kzfb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rapids" /></template>
<style>
.nn0kzfb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6C4.5 4 7 4 9 6s4.5 2 6.5 0s4.5-2 6-.5M2.5 12c2-2 4.5-2 6.5 0s4.5 2 6.5 0s4.5-2 6-.5M3 21.5c.5-4 6-4 6.5 0m2.5 0c.5-3.5 6-4.5 9 0");
}

</style>

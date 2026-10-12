<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2wzmxblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thyroid" /></template>
<style>
.b2wzmxblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12.25V9.5C9 8 8 7 6.75 7q-2.25 0-3 3l-.5 4.75C3 17 4.5 18.5 6.25 18.5c1.5 0 2.75-1.25 2.75-2.75h6c0 1.5 1.25 2.75 2.75 2.75c1.75 0 3.25-1.5 3-3.75l-.5-4.75q-.75-3-3-3C16 7 15 8 15 9.5v2.75Zm3-9.5v9.5m0 3.5v5.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yihvkdb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:root-cutting" /></template>
<style>
.yihvkdb1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.5v10M12 8c0-3 2.5-5 6-5c0 3.5-2.5 5-6 5Zm0 3c0-3-2.5-5-6-5c0 3.5 2.5 5 6 5Zm0 4.5V21m0-5.5q-3.5 1-4 5m4-5q3.5 1 4 5");
}

</style>

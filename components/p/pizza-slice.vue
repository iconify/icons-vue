<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z9p62th2h"/><path class="qd-m-94ac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pizza-slice" /></template>
<style>
.qd-m-94ac {
  d: path("M8.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4 2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9p62th2h {
  d: path("M12 21L3.5 5.5h17Z");
}

</style>

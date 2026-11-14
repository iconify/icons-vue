<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fgqqg8b1s"/><path class="xqrqdoayz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-salad" /></template>
<style>
.fgqqg8b1s {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xqrqdoayz {
  d: path("M7 11h10a5 5 0 0 1-10 0Zm3 0c0-3 2-4 4.5-4.25c.25 2.25-1 4.25-1.75 4.25");
}

</style>

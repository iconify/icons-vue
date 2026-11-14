<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vcl9wjd4h"/><path class="tl-7l28gj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-heart" /></template>
<style>
.tl-7l28gj {
  d: path("M18 21s-3-1.75-3-4c0-1 .75-1.75 1.75-1.75c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75c1 0 1.75.75 1.75 1.75c0 2.25-3 4-3 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcl9wjd4h {
  d: path("M12.785 19.577L9 18l-6 2.5V6l6-2.5L15 6l6-2.5v9.3M9 3.5V18m6-12v3.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="exc7-ybws"/><path class="qu3dd11rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:product-rating" /></template>
<style>
.exc7-ybws {
  d: path("M12.2 19.5H8.5l-5-7.5l5-7.5h11v6.8M8.25 12h.01");
}

.qu3dd11rz {
  d: path("m17.25 13l1.176 2.382l2.628.382l-1.902 1.854l.449 2.618L17.25 19l-2.351 1.236l.449-2.618l-1.902-1.854l2.628-.382Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

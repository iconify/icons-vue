<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cs9rnyhsz"/><path class="rt0uypbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:secure-data-room" /></template>
<style>
.cs9rnyhsz {
  d: path("M12.183 19.834L11 20.5L3 16V7l8-4.5L19 7v5.321");
}

.rt0uypbxx {
  d: path("m3 7l8 4.5L19 7m-8 4.5v9m4-3h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

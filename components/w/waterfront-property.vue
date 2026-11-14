<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ylii8sbgc"/><path class="ldhiy1bbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waterfront-property" /></template>
<style>
.ldhiy1bbe {
  d: path("M10.5 13.5v-3h3v3M3 17q1.5-1.25 3 0t3 0t3 0t3 0t3 0t3 0M3 20.5q1.5-1.25 3 0t3 0t3 0t3 0t3 0t3 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylii8sbgc {
  d: path("m6 9l6-6l6 6v4.5H6Zm-3.5 4.5h19");
}

</style>

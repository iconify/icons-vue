<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vd--y3b4j"/><path class="riew-sbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-journal" /></template>
<style>
.riew-sbfu {
  d: path("M11.25 13c.75 1.5 4.25 1.5 5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vd--y3b4j {
  d: path("M5 2.5h14v19H5Zm3.5 0v19m3.5-12h.01m3.49 0h.01");
}

</style>

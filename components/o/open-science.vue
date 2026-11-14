<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kxmu5me1j"/><path class="ejkj6th1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-science" /></template>
<style>
.ejkj6th1k {
  d: path("M16.25 15.5h4.25v4.25");
}

.kxmu5me1j {
  d: path("M21 12.593V4.5c-3-.5-7 0-9 1.5c-2-1.5-6-2-9-1.5v14c3-.5 7 0 9 1.5q.161-.121.339-.233M12 6v14m3 1l5.25-5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

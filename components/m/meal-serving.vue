<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ig269_-al"/><path class="hfmqhy5ar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meal-serving" /></template>
<style>
.hfmqhy5ar {
  d: path("M10.5 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM7 19.5h10");
}

.ig269_-al {
  d: path("M3 16.5a9 9 0 0 1 18 0m-18.5 0h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

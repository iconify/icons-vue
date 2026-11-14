<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rf4vy8tks"/><path class="ohbd1db0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:party-balloon" /></template>
<style>
.ohbd1db0m {
  d: path("M8.619 7.594a3.5 3.5 0 0 1 2.475-2.475");
}

.rf4vy8tks {
  d: path("M12 15c-3.25 0-6-3-6-6.5c0-3.25 2.75-5.75 6-5.75s6 2.5 6 5.75c0 3.5-2.75 6.5-6 6.5Zm0 0l1.25 1.75h-2.5Zm0 1.75c0 1.75 1.25 2.75.5 4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

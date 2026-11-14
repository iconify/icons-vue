<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvodh26ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roots-spread" /></template>
<style>
.cvodh26ax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9h19M12 9V6.5m0 0Q8.5 6.5 8 3q3.5 0 4 3.5q.5-3.5 4-3.5q-.5 3.5-4 3.5M12 9v12m0-9q-6 .5-9 6m9-6q6 .5 9 6M6.5 13.75Q6 17 7.5 20.5m10-6.75q.5 3.25-1 6.75");
}

</style>

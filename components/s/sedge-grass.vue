<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvojgob6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sedge-grass" /></template>
<style>
.xvojgob6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 20.5Q5.5 14 2.5 10M9 20.5Q8.5 11 6.5 4M12 20.5v-18m3 18Q15.5 11 17.5 4m.5 16.5q.5-6.5 3.5-10.5m-18 10.5h17");
}

</style>

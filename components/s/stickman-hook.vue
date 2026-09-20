<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k72dufayu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stickman-hook" /></template>
<style>
.k72dufayu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.656 10.407a40.4 40.4 0 0 1-5.488 4.864m-1.617 1.385l-4.106 3.2m-8.305 7.472l2.47 2.707l-2.913 1.688l-.517 1.37m-3.914-6.8l7.72-2.714m.397.217l-3.478 3.75l-4.9 6.25l-.396 1.382m13.896-14.67a3.617 3.617 0 1 1-3.616-3.617a3.617 3.617 0 0 1 3.616 3.617M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>

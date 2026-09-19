<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="exrvy4-5k"/><path class="j9tt8jixt"/><path class="pddtocbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:materializr" /></template>
<style>
.exrvy4-5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.688 42.233L8.722 35.142V14.34L24 5.5l15.278 8.84v20.802l-11.051 7.147");
}

.j9tt8jixt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.25 12.187l3.77 2.177l-7.92 5.973l-7.705-5.756l3.89-2.246m.049-4.074v8.7m7.272-8.959v9.522m-3.549-11.34v14.153m-4.239 21.815l.083-7.71l-4.91-2.834v-9.842L24 28.085l8.537-6.06v9.48l-4.415 3.375v7.476m-.516-16.781v9.304m-7.272-9.273v9.028");
}

.pddtocbeo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.334 34.481L24 42.5l3.606-7.835");
}

</style>

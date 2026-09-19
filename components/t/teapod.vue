<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkbuykb4k"/><path class="obvy6bbtg"/><path class="m-i-hsbgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:teapod" /></template>
<style>
.bkbuykb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.457 14.136h10.617s10.07 13.174-4.464 20.58h-6.153");
}

.m-i-hsbgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.687 20.36a5.78 5.78 0 0 1-4.631-4.814C7.585 13.79 6.506 14 6.506 14H3.5s1.335.113 2.514 6.67a9.97 9.97 0 0 0 7.334 7.873");
}

.obvy6bbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.038 17.577c5.712-12.724 13.404 6.418.114 11.35M26.248 14.136H15.63S5.56 27.31 20.095 34.716h6.153");
}

</style>

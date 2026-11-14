<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vd3-2qb6l"/><path class="p5qarxl_j"/><path class="kjx4zbb2m"/><path class="ekdsuac_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pylon-sign" /></template>
<style>
.ekdsuac_o {
  d: path("M10 13h4m-4 3.5h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjx4zbb2m {
  fill: currentColor;
  d: path("M12.22 5.822za.95.95 0 0 0 .833.604a.236.236 0 0 1 .136.419a.95.95 0 0 0-.318.979a.236.236 0 0 1-.357.259a.95.95 0 0 0-1.028 0a.236.236 0 0 1-.357-.259a.95.95 0 0 0-.318-.979a.236.236 0 0 1 .136-.419a.95.95 0 0 0 .833-.604a.236.236 0 0 1 .44 0");
}

.p5qarxl_j {
  d: path("M9 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.vd3-2qb6l {
  d: path("M10.117 2.5h3.766a1.75 1.75 0 0 1 1.744 1.612l1.224 15.5a1.75 1.75 0 0 1-1.745 1.888H8.894a1.75 1.75 0 0 1-1.745-1.888l1.224-15.5A1.75 1.75 0 0 1 10.117 2.5M2.5 21.5h19");
}

</style>

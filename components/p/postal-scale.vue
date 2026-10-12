<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u12evybon"/><path class="uh4dc4daa"/><path class="gr3i8rb8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:postal-scale" /></template>
<style>
.gr3i8rb8r {
  d: path("M9.25 18.75a2.75 2.75 0 0 1 5.5 0m-2.75 0l1.25-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u12evybon {
  width: 9.5px;
  height: 6px;
  x: 7.25px;
  y: 4.25px;
  rx: 1px;
}

.uh4dc4daa {
  d: path("M12 4.25v2.5m-8.25 3.5h16.5m-8.25 0V13m-5.25 0h10.5q1.5 0 1.77 1.48l.96 5.29q.27 1.48-1.23 1.48H5.25q-1.5 0-1.23-1.48l.96-5.29Q5.25 13 6.75 13");
}

</style>

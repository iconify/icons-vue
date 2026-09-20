<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z81xltbwu"/><path class="gswswg2-b"/><path class="ef5yg46po"/><path class="tggnnsjln"/><path class="uxcq0c75d"/><path class="rb4zd2b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rest-outline-thin" /></template>
<style>
.ef5yg46po {
  d: path("M10 7h8");
}

.gswswg2-b {
  d: path("M5 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rb4zd2b4c {
  d: path("M10 17h5");
}

.tggnnsjln {
  d: path("M2 17a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

.uxcq0c75d {
  d: path("M5 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.z81xltbwu {
  d: path("M2 7a3 3 0 0 1 3 -3h14a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3");
}

</style>

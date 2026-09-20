<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pv9xj1b7g"/><path class="gzf8q_b5i"/><path class="x7gyblbnl"/><path class="i33dqh0th"/><path class="czv374byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-save-outline-thin" /></template>
<style>
.czv374byt {
  d: path("M10 16h11");
}

.gzf8q_b5i {
  d: path("m5 9 2 2 -2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i33dqh0th {
  d: path("M10 11h11");
}

.pv9xj1b7g {
  d: path("M2 11h5");
}

.x7gyblbnl {
  d: path("M10 6h11");
}

</style>

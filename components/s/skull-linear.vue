<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sq7lb-bwb"/><path class="oqu69y0pu"/><path class="urql2sbeg"/><path class="x91lodcov"/><path class="gc_ullwtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skull-linear" /></template>
<style>
.gc_ullwtz {
  d: path("M13.3301 22V19.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqu69y0pu {
  d: path("M10.5 11C10.5 12.1046 9.6046 13 8.5 13C7.3954 13 6.5 12.1046 6.5 11C6.5 9.8954 7.3954 9 8.5 9C9.6046 9 10.5 9.8954 10.5 11Z");
}

.sq7lb-bwb {
  d: path("M8 18C5 16.8 3 13.8 3 10.5C3 5.8 7 2 12 2C17 2 21 5.8 21 10.5C21 13.8 19 16.8 16 18V19.8C16 20.8371 16 21.3556 15.6778 21.6778C15.3556 22 14.8371 22 13.8 22H10.2C9.1629 22 8.6444 22 8.3222 21.6778C8 21.3556 8 20.8371 8 19.8V18Z");
}

.urql2sbeg {
  d: path("M17.5 11C17.5 12.1046 16.6046 13 15.5 13C14.3954 13 13.5 12.1046 13.5 11C13.5 9.8954 14.3954 9 15.5 9C16.6046 9 17.5 9.8954 17.5 11Z");
}

.x91lodcov {
  d: path("M10.6699 22V19.5");
}

</style>

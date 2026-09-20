<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jea8fibeb"/><path class="e3tmhtu7v"/><path class="gl2wyfu4j"/><path class="xsx-llilr"/><path class="tn1eizb9z"/><path class="zokbyhqlb"/><path class="xq1pi7btv"/><path class="qi3wr9i3q"/><path class="q686vz2zk"/><path class="zky22zblb"/><path class="j4nym3cre"/><path class="m1z_l4h_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:traceroute-duotone-thin" /></template>
<style>
.e3tmhtu7v {
  fill: currentColor;
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gl2wyfu4j {
  fill: currentColor;
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4nym3cre {
  d: path("m6 16 2 -2");
}

.jea8fibeb {
  fill: currentColor;
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m1z_l4h_u {
  d: path("m12 11 2 -2");
}

.q686vz2zk {
  d: path("M14 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.qi3wr9i3q {
  d: path("M8 13a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.tn1eizb9z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 16 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xq1pi7btv {
  d: path("M2 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xsx-llilr {
  fill: currentColor;
  d: path("M20 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zky22zblb {
  d: path("M20 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zokbyhqlb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 11 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

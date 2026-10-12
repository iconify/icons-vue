<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ojhsutbme"/><rect class="d8t_mcb6h"/><rect class="ekbb6luaw"/><path class="j_rdrymqn"/><path class="axfc1_nyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traffic-court" /></template>
<style>
.axfc1_nyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 15.25v6");
}

.d8t_mcb6h {
  width: 9.5px;
  height: 2.5px;
  x: 2.75px;
  y: 18.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.ekbb6luaw {
  width: 6.5px;
  height: 12.5px;
  x: 13.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.j_rdrymqn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 5.75h.01M17 9h.01M17 12.25h.01");
}

.ojhsutbme {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.59 8.12l3.53-3.53q.71-.71 1.42 0l.87.87q.71.71 0 1.42l-3.53 3.53q-.71.71-1.42 0l-.87-.87q-.71-.71 0-1.42m4.06.53L11 12");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l6s4zsbdw"/><path class="gi3y_ucsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stream-tv" /></template>
<style>
.gi3y_ucsm {
  d: path("m11.02 12.3l2.46 1.4q.52.3 0 .6l-2.46 1.4q-.52.3-.52-.3v-2.8q0-.6.52-.3m-3.77 6.45v2.5m9.5-2.5v2.5M10 6.5a3 3 0 0 1 4 0M8 4.27a6 6 0 0 1 8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6s4zsbdw {
  width: 18.5px;
  height: 9.5px;
  x: 2.75px;
  y: 9.25px;
  rx: 2.5px;
}

</style>

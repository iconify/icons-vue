<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uwjrx0j1q"/><path class="w_co2vb4u"/><path clip-rule="evenodd" class="gd25r_74b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-alert-duotone" /></template>
<style>
.gd25r_74b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 13C13 13.5523 12.5523 14 12 14C11.4477 14 11 13.5523 11 13C11 12.4477 11.4477 12 12 12C12.5523 12 13 12.4477 13 13Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uwjrx0j1q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13.5L2 6C2 3.7908 3.7908 2 6 2L18 2C20.2092 2 22 3.7908 22 6L22 14C22 16.2092 20.2092 18 18 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21Z");
  stroke: none;
}

.w_co2vb4u {
  d: path("M12 7L12 9");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cq08pqb2k"/><path class="l60eq6b_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:male-female-symbol" /></template>
<style>
.cq08pqb2k {
  d: path("M8.5 5.25a4.75 4.75 0 1 1 0 9.5a4.75 4.75 0 1 1 0-9.5m0 9.5v6.5m-2.5-3h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l60eq6b_h {
  d: path("M14 5.25a4.75 4.75 0 1 1 0 9.5a4.75 4.75 0 1 1 0-9.5m3.36 1.39l3.89-3.89m-4.25 0h4.25V7");
}

</style>

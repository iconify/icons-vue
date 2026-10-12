<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lwazmzbma"/><path class="yvvwcmb6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-layers" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lwazmzbma {
  d: path("m3.92 8.32l2.41-.89q1.17-.43 2.34 0l2.41.89q1.17.43 2.34 0l2.41-.89Q17 7 17 8.25v10q0 1.25-1.17 1.68l-2.41.89q-1.17.43-2.34 0l-2.41-.89q-1.17-.43-2.34 0l-2.41.89q-1.17.43-1.17-.82V10q0-1.25 1.17-1.68M7.5 7v12.5m4.75-10.75v12.5");
}

.yvvwcmb6l {
  d: path("m7 4.5l4.75-1.75L16.5 4.5l4.75-1.75v13.5l-1.75.65");
}

</style>

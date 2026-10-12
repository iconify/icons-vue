<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cm8lo6v1l"/><path class="y6e5_vbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:privacy-law" /></template>
<style>
.cm8lo6v1l {
  d: path("m12 2.75l6.6 2.45a1 1 0 0 1 .65.94v5.26c0 4.4-2.9 7.6-7.25 9.85C7.65 19 4.75 15.8 4.75 11.4V6.14a1 1 0 0 1 .65-.94Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y6e5_vbro {
  d: path("M13.75 8.25c-.35-.65-.95-1-1.75-1c-1 0-1.75.6-1.75 1.4c0 1.95 3.5 1.75 3.5 3.7m-3.5 3.4c.35.65.95 1 1.75 1c1 0 1.75-.6 1.75-1.4c0-1.95-3.5-1.75-3.5-3.7");
}

</style>

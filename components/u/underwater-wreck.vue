<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gfxyuwx8l"/><path class="go4arfbfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:underwater-wreck" /></template>
<style>
.gfxyuwx8l {
  d: path("m3 13.75l14 2.5l1.5-1.5l2 3l-1.5 3H7.5Z");
}

.go4arfbfa {
  d: path("m10 15l3-6l1.5 1M3 4.25q3-2.625 6 0t6 0t6 0M2.5 20.75h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

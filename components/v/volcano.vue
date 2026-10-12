<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="byvtvouew"/><path class="ehu3gubgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volcano" /></template>
<style>
.byvtvouew {
  d: path("M9.25 9.25h5.5l6.1 10.4a1 1 0 0 1-.86 1.6H4.01a1 1 0 0 1-.86-1.6Z");
}

.ehu3gubgw {
  d: path("M12 9.25v3.5L10 15m2-12.25v3.5m-4.25-2.5l1.5 2.5m7-2.5l-1.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

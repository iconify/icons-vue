<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z_1z-qbos"/><path class="ky4omnbla"/><path class="m5hpqyobl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pension-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.m5hpqyobl {
  d: path("M9.5 9.5h5l-5 5h5Z");
}

.z_1z-qbos {
  fill: currentColor;
  d: path("M9.5 9.5h5l-5 5h5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vu8qf_bet"/><path class="b371uj3tj"/><path class="j-t96eb1w"/><path class="iaoq7pb9m"/><path class="di73vubuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:node-drain-outline-regular" /></template>
<style>
.b371uj3tj {
  d: path("M10 8h7");
}

.di73vubuu {
  d: path("m15 14 2 2 -2 2");
}

.iaoq7pb9m {
  d: path("M10 16h7");
}

.j-t96eb1w {
  d: path("m15 6 2 2 -2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vu8qf_bet {
  d: path("M3 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lo7kp72nh"/><path class="mjuhvrbig"/><path class="zg6stybep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:surrogate-key-outline-regular" /></template>
<style>
.lo7kp72nh {
  d: path("M3 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.mjuhvrbig {
  d: path("M9 8h9v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zg6stybep {
  d: path("M16 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

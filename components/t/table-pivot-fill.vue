<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ba-zjvr9e"/><path class="ef1982bwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-pivot-fill" /></template>
<style>
.ba-zjvr9e {
  fill: currentColor;
  d: path("M2 8H8V20H5C3.34315 20 2 18.65685 2 17V8Z");
  stroke: none;
}

.ef1982bwa {
  d: path("M2 8H20V5C20 3.34315 18.65685 2 17 2H5C3.34315 2 2 3.34315 2 5V17C2 18.65685 3.34315 20 5 20H8V8M20 12V17C20 18.65685 18.65685 20 17 20H12M18 14L20 12L22 14M14 18L12 20L14 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jon3jyusz"/><path class="x4nz41duv"/><path class="z55i2tbmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:team-jersey-duotone-regular" /></template>
<style>
.jon3jyusz {
  fill: currentColor;
  d: path("m3 9 5 -5h8l5 5 -4 4v7H7v-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x4nz41duv {
  d: path("m3 9 5 -5h8l5 5 -4 4v7H7v-7Z");
}

.z55i2tbmp {
  d: path("m9 4 3 3 3 -3");
}

</style>

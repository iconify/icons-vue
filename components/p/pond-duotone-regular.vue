<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oi9g91b_q"/><path class="b-af79bpy"/><path class="hk8a83bva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pond-duotone-regular" /></template>
<style>
.b-af79bpy {
  d: path("M12 7c5 0 9 2 9 6s-4 6 -9 6 -9 -2 -9 -6 4 -6 9 -6");
}

.hk8a83bva {
  d: path("M8 15c2 -2 6 -2 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oi9g91b_q {
  fill: currentColor;
  d: path("M12 7c5 0 9 2 9 6s-4 6 -9 6 -9 -2 -9 -6 4 -6 9 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

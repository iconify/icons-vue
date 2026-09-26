<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s9_zf1bnm"/><path class="m3pl5ubmo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plug-duotone" /></template>
<style>
.m3pl5ubmo {
  fill: currentColor;
  d: path("M8 6L16 6C18.2092 6 20 7.7908 20 10L20 11C20 15.4183 16.4183 19 12 19C7.5817 19 4 15.4183 4 11L4 10C4 7.7908 5.7908 6 8 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s9_zf1bnm {
  stroke-opacity: 0.4;
  d: path("M9 2L9 7M15 2L15 7M12 18L12 22");
}

</style>

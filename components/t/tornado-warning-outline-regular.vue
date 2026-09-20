<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uweslxo3x"/><path class="s09hy0b0y"/><path class="e8vupfb9c"/><path class="np1vk1eeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tornado-warning-outline-regular" /></template>
<style>
.e8vupfb9c {
  d: path("M9.5 14h5");
}

.np1vk1eeq {
  d: path("M11 17h2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.uweslxo3x {
  d: path("M12 3.5 21.5 20h-19Z");
}

</style>

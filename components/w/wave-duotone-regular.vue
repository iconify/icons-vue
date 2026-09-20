<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eyjrjq0ck"/><path class="mbt4yzbhr"/><path class="w6w8km5nw"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wave-duotone-regular" /></template>
<style>
.eyjrjq0ck {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 14a9 9 0 0 1 16 -5 4.5 4.5 0 0 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w6w8km5nw {
  d: path("M3 14a9 9 0 0 1 16 -5 4.5 4.5 0 0 0 -7 0");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>

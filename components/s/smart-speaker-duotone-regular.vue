<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo5a1lb8y"/><path class="nj-8yn50i"/><path class="u2j6nmbhr"/><path class="c4khiwgvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smart-speaker-duotone-regular" /></template>
<style>
.c4khiwgvb {
  d: path("M8 15h8");
}

.nj-8yn50i {
  d: path("M6 8c0 -2 12 -2 12 0v11c0 2 -12 2 -12 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u2j6nmbhr {
  d: path("M6 8c0 2 12 2 12 0");
}

.wo5a1lb8y {
  fill: currentColor;
  d: path("M6 8c0 -2 12 -2 12 0v11c0 2 -12 2 -12 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

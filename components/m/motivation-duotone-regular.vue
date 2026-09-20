<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-p54wt7w"/><path class="v20aanbzl"/><path class="so5p-db7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motivation-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.so5p-db7p {
  d: path("M7 12h3l3 -3V5h2.5v5H19v10H7Z");
}

.v20aanbzl {
  d: path("M7 12H3v8h4");
}

.w-p54wt7w {
  fill: currentColor;
  d: path("M7 12h3l3 -3V5h2.5v5H19v10H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

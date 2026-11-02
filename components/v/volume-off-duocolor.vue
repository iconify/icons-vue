<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="b7k2iv20o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-off-duocolor" /></template>
<style>
.axcf-wb4p {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

.b7k2iv20o {
  d: path("M8 8a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h1c.64 0 1.36.36 2 1l2 2c.369.369 1-.262 1-1v-4m0-6V6c0-.738-.631-1.369-1-1l-1 1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

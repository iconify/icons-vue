<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a2d4gor6c"/><path class="w8co5vb5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-help-duocolor" /></template>
<style>
.a2d4gor6c {
  stroke-opacity: 0.4;
  d: path("M10 12a2 2 0 1 1 2 2m0 3h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w8co5vb5n {
  d: path("m13.728 4.992l7 12C21.505 18.326 20.544 20 19 20H5c-1.544 0-2.505-1.674-1.728-3.008l7-12c.772-1.323 2.684-1.323 3.456 0");
}

</style>

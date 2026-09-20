<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="id4vqxf8c"/><path class="qlw91sbif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overfit-gap-outline-regular" /></template>
<style>
.id4vqxf8c {
  d: path("m4 14 5 -5h11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlw91sbif {
  d: path("m4 19 5 -5h4l4 4");
}

</style>

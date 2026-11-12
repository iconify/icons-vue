<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wx9p5uqgi"/><path class="p9nk_hb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-clock-corner-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9nk_hb0c {
  d: path("M8 20H4V4h16v4");
}

.wx9p5uqgi {
  stroke-opacity: 0.4;
  d: path("M12 17a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>

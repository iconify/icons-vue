<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="snkvu_bzj"/><path class="j9gdhp6om"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-problem-duocolor" /></template>
<style>
.j9gdhp6om {
  d: path("M9 16c1.427-2.14 4.573-2.14 6 0m-9-3c1.484-1.78 3.682-3 6-3m-9 0c2.285-2.57 5.56-4 9-4m0 13h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.snkvu_bzj {
  stroke-opacity: 0.4;
  d: path("m17 5l4 4m0-4l-4 4");
}

</style>

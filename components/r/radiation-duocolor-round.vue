<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ujawvmq4f"/><path class="dvu2lvb6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiation-duocolor-round" /></template>
<style>
.dvu2lvb6d {
  d: path("M16 12h5a8.97 8.97 0 0 0-5-8l-2 4a4.22 4.22 0 0 1 2 4m-6-4L8 4a8.97 8.97 0 0 0-5 8h5a4.22 4.22 0 0 1 2-4m0 8l-2 4a8.94 8.94 0 0 0 8 0l-2-4a4.47 4.47 0 0 1-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ujawvmq4f {
  stroke-opacity: 0.4;
  d: path("M12 12h.01");
}

</style>

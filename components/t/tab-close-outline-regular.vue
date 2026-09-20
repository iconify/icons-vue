<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="oh3t_sdfd"/><path class="b4nrz0b6r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-close-outline-regular" /></template>
<style>
.b4nrz0b6r {
  d: path("m20.5 10.5 -5 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oh3t_sdfd {
  d: path("m15.5 10.5 5 5");
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>

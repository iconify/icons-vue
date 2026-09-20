<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m8ek3-bfo"/><path class="eisa2cb9u"/><path class="r_wvrg-qd"/><path class="o3k-rmbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:takeoff-outline-regular" /></template>
<style>
.eisa2cb9u {
  d: path("M2 22h20");
}

.m8ek3-bfo {
  d: path("m12 3 2 2v4l5.5 5.5H14V17l2 2H8l2 -2v-2.5H4.5L10 9V5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o3k-rmbxb {
  d: path("M2 2h3v3");
}

.r_wvrg-qd {
  d: path("m2 5 3 -3");
}

</style>

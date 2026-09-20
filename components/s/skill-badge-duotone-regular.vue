<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cjm330b0r"/><path class="n-7xnfbas"/><path class="vtc00ob6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skill-badge-duotone-regular" /></template>
<style>
.cjm330b0r {
  fill: currentColor;
  d: path("m12 3 7 7v4l-7 7 -7 -7v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n-7xnfbas {
  d: path("m12 3 7 7v4l-7 7 -7 -7v-4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vtc00ob6f {
  d: path("m8 10 3 3 5 -5");
}

</style>

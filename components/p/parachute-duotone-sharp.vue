<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k0ivz5bup"/><path class="b9dcgf9fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parachute-duotone-sharp" /></template>
<style>
.b9dcgf9fp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 9c0-4 4-6 9-6s9 2 9 6q-4.5-3-9 0q-4.5-3-9 0m0 0l9 9l9-9m-9 0v12m-3 0h6");
}

.ft5dv1b6b {
  fill: none;
}

.k0ivz5bup {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 9c0-4 4-6 9-6s9 2 9 6c-2.998-1.997-6.002-1.997-9 0c-2.998-1.997-6.002-1.997-9 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r66p82bnb"/><path class="dn_yk0bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiation-duotone-round" /></template>
<style>
.dn_yk0bps {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 12h5a8.97 8.97 0 0 0-5-8l-2 4a4.22 4.22 0 0 1 2 4m-6-4L8 4a8.97 8.97 0 0 0-5 8h5a4.22 4.22 0 0 1 2-4m0 8l-2 4a8.94 8.94 0 0 0 8 0l-2-4a4.47 4.47 0 0 1-4 0m2-4h.01");
}

.ft5dv1b6b {
  fill: none;
}

.r66p82bnb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 13H2.995A1 1 0 0 1 2 11.995A9.95 9.95 0 0 1 3.516 6.76a9.96 9.96 0 0 1 4.041-3.657a1 1 0 0 1 1.337.45l2 4a1 1 0 0 1-.373 1.3a3.17 3.17 0 0 0-1.2 1.307a3.17 3.17 0 0 0-.326 1.745A1 1 0 0 1 8 13m5.106-5.447l2-4a1 1 0 0 1 1.337-.45a10 10 0 0 1 2.294 1.564A9.96 9.96 0 0 1 22 11.995V12a1 1 0 0 1-1 1h-5a1 1 0 0 1-.995-1.095a3.17 3.17 0 0 0-.326-1.745a3.17 3.17 0 0 0-1.2-1.307a1 1 0 0 1-.373-1.3m1.788 8l2 4a1 1 0 0 1-.447 1.341A9.8 9.8 0 0 1 12 21.944a9.8 9.8 0 0 1-4.447-1.05a1 1 0 0 1-.447-1.341l2-4a1 1 0 0 1 1.341-.447a3.4 3.4 0 0 0 1.553.366a3.4 3.4 0 0 0 1.553-.366a1 1 0 0 1 1.341.447");
}

</style>

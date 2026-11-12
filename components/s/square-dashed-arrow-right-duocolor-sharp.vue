<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bifj1rbsn"/><path class="w66e9pbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-arrow-right-duocolor-sharp" /></template>
<style>
.bifj1rbsn {
  stroke-opacity: 0.4;
  d: path("m13 15l3-3l-3-3m3 3H8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w66e9pbhz {
  d: path("M3 6V3h3m12 0h3v3m0 12v3h-3M6 21H3v-3m7-15h4m7 7v4m-7 7h-4m-7-7v-4");
}

</style>

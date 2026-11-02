<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s-q6s911c"/><path class="u6n-kfbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s-q6s911c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 16c0-.265.105-.52.293-.707l12-12a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-12 12A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1Z");
}

.u6n-kfbak {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 16L16 4l4 4L8 20m0 0H4v-4m7-11L9 7m10 6l-2 2m-4-8L9 3L3 9l4 4m10-2l4 4l-6 6l-4-4");
}

</style>

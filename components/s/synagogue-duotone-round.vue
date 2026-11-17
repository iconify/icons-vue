<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f3srt45sn"/><path class="eoagpcb9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-duotone-round" /></template>
<style>
.eoagpcb9p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H8a4 4 0 0 1-4-4v-7c0-1.226.774-2.387 2-3l4-2a4.47 4.47 0 0 1 4 0l4 2c1.226.613 2 1.774 2 3v7a4 4 0 0 1-4 4zm0-12l3.464 6H8.536Zm0 8l3.464-6H8.536Z");
}

.f3srt45sn {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 17v-7c.001-1.305.863-2.431 2-3l4-2a4.47 4.47 0 0 1 4 0l4 2c1.137.569 1.999 1.695 2 3v7a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4");
}

.ft5dv1b6b {
  fill: none;
}

</style>

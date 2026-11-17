<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mb6g4zboh"/><path class="mv5m2elnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pig-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mb6g4zboh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 3c2 0 4 1 5 2c1.5-.3 4.5-.3 6 0c1-1 3-2 5-2c0 1 0 3-1 5c1.618 1.62 2 3.795 2 6c0 4-2.5 7-6 7H9c-3.5 0-6-3-6-7c0-2.205.382-4.38 2-6c-1-2-1-4-1-5m6.01 10H10a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

.mv5m2elnr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 8C4 6 4 4 4 3c2 0 4 1 5 2c1.5-.3 4.5-.3 6 0c1-1 3-2 5-2c0 1 0 3-1 5c1.5 1.5 2 3.5 2 6c0 4-2.5 7-6 7H9c-3.5 0-6-3-6-7c0-2.5.5-4.5 2-6m4 0h.01M15 8h.01M12 11c2.76 0 5 1.34 5 3s-2.24 3-5 3s-5-1.34-5-3s2.24-3 5-3m-2 3h.01M14 14h.01");
}

</style>

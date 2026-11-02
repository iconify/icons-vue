<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mzknavjcm"/><path class="fkdpf6eac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-dim-duocolor-round" /></template>
<style>
.fkdpf6eac {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.mzknavjcm {
  stroke-opacity: 0.4;
  d: path("M19 12h.01m-2.06 4.95h.01M12 19h.01m-4.96-2.05h.01M5 12h.01m2.04-4.95h.01M12 5h.01m4.94 2.05h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

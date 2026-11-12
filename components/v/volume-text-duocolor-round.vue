<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c86uuzbhr"/><path class="hfbj_43ii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-text-duocolor-round" /></template>
<style>
.c86uuzbhr {
  stroke-opacity: 0.4;
  d: path("M3 9h6M6 9v6");
}

.hfbj_43ii {
  d: path("m16 10l4-4c.369-.369 1-.369 1 0v12c0 .369-.631.369-1 0l-4-4h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

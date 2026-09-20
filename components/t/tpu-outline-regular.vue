<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j6v5-qbsu"/><path class="d68m7u0nn"/><path class="i5z9c0bsl"/><path class="wniafzb5r"/><path class="ao-h93max"/><path class="cdyau8b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tpu-outline-regular" /></template>
<style>
.ao-h93max {
  d: path("M9 19v3");
}

.cdyau8b6j {
  d: path("M15 19v3");
}

.d68m7u0nn {
  d: path("M9.5 12A2.5 2.5 0 0 1 12 9.5a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5A2.5 2.5 0 0 1 9.5 12");
}

.i5z9c0bsl {
  d: path("M9 2v3");
}

.j6v5-qbsu {
  d: path("M5 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wniafzb5r {
  d: path("M15 2v3");
}

</style>

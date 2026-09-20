<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uih_zvhtv"/><path class="sg0msuxxt"/><path class="b6bpk4b8h"/><path class="fevuzkbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:microscope-outline-regular" /></template>
<style>
.b6bpk4b8h {
  d: path("M11 17v-6l5 -5");
}

.fevuzkbbx {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sg0msuxxt {
  d: path("M7 21v-4h8");
}

.uih_zvhtv {
  d: path("M4 21h16");
}

</style>

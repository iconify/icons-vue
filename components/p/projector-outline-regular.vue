<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vvyrl1k7r"/><path class="na074v-mn"/><path class="j49v8ng1j"/><path class="q1ae0k4gd"/><path class="er1zo2e1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:projector-outline-regular" /></template>
<style>
.er1zo2e1s {
  d: path("M20 4v17");
}

.j49v8ng1j {
  d: path("m14 9 4 -4");
}

.na074v-mn {
  d: path("M6 12.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1ae0k4gd {
  d: path("m14 16 4 4");
}

.vvyrl1k7r {
  d: path("M2 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>

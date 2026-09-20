<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i-zodcc2a"/><path class="x0l-yf_vd"/><path class="ox_kf9bfs"/><path class="x81m3s-aw"/><path class="r2-193ooz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-http-outline-regular" /></template>
<style>
.i-zodcc2a {
  d: path("M16.5 4H19a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3h-5a3 3 0 0 1 -3 -3V7l3 -3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox_kf9bfs {
  d: path("m8 6 3 3 -3 3");
}

.r2-193ooz {
  d: path("m5 12 -3 3 3 3");
}

.x0l-yf_vd {
  d: path("M2 9h9");
}

.x81m3s-aw {
  d: path("M2 15h9");
}

</style>

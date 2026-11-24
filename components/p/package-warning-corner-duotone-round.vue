<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ftbyj6eil"/><path class="ax1z0dcvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-warning-corner-duotone-round" /></template>
<style>
.ax1z0dcvu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 8v8a4 4 0 0 0 4 4M4 8l1-2c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2M4 8h16m-3 6v4m0 3h.01");
}

.ft5dv1b6b {
  fill: none;
}

.ftbyj6eil {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 6c.569-1.137 1.695-1.999 3-2h8c1.305.001 2.431.863 3 2l1 2H4Z");
}

</style>

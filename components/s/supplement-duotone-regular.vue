<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rn5f9dbtw"/><path class="bjjj83beu"/><path class="ne8bcmb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:supplement-duotone-regular" /></template>
<style>
.bjjj83beu {
  d: path("M6 21V9h12v12Z");
}

.ne8bcmb7x {
  d: path("M5 9V6h14v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rn5f9dbtw {
  fill: currentColor;
  d: path("M6 21V9h12v12Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

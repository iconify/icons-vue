<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kt5437z2p"/><path clip-rule="evenodd" class="vfpo-ybma"/><path class="b7gdp2bcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-move-down-duotone" /></template>
<style>
.b7gdp2bcd {
  d: path("M12 16V22M9 19L12 22L15 19");
}

.kt5437z2p {
  stroke-opacity: 0.4;
  d: path("M5 19.8284C3.8014 19.4046 3 18.2713 3 17L3 11M21 11L21 17C21 18.2713 20.1986 19.4046 19 19.8284");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vfpo-ybma {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 5C2 2.7909 3.7909 1 6 1L18 1C20.2091 1 22 2.7909 22 5L22 12L2 12Z");
  stroke: none;
}

</style>

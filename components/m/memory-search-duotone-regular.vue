<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kad_nk32x"/><path class="qd2a5rnak"/><path class="sfb1ntbvv"/><path class="zwghjjvbs"/><path class="k5vsxkcxh"/><path class="vfk29flre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-search-duotone-regular" /></template>
<style>
.k5vsxkcxh {
  d: path("M12 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.kad_nk32x {
  fill: currentColor;
  d: path("M12 10a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qd2a5rnak {
  d: path("M2 6h7");
}

.sfb1ntbvv {
  d: path("M2 11h7");
}

.vfk29flre {
  d: path("m19 13 2.5 2.5");
}

.zwghjjvbs {
  d: path("M2 16h7");
}

</style>

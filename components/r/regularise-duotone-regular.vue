<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h4xiao5dx"/><path class="be306ynmy"/><path class="iqi_aabed"/><path class="xgrfb-bqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:regularise-duotone-regular" /></template>
<style>
.be306ynmy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h4xiao5dx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 5 -5 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.iqi_aabed {
  d: path("m3 15 5 -5 5 5 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>

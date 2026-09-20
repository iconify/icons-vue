<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="sixdm4bhp"/><path class="d223d_x9q"/><path class="nuz6-76is"/><path class="yngda3bvc"/><path class="ecph9tq5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:semantic-chunk-outline-regular" /></template>
<style>
.d223d_x9q {
  d: path("M3 12h6");
}

.ecph9tq5i {
  d: path("M3 18h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuz6-76is {
  d: path("M15 12h6");
}

.sixdm4bhp {
  d: path("M3 9h14");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>

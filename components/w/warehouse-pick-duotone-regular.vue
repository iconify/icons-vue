<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_oqy2n_y"/><path class="ntbbvlkxf"/><path class="e77gki8ci"/><path class="jdqylbbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:warehouse-pick-duotone-regular" /></template>
<style>
.e77gki8ci {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

.jdqylbbkf {
  d: path("m9 14 2 2 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ntbbvlkxf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 14 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o_oqy2n_y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 20V10l3 -3h14l3 3v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

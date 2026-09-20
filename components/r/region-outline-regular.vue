<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_ssmh9ez"/><path class="qnsgwgb-f"/><path class="ae-e09b3w"/><path class="lsvp9tyne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:region-outline-regular" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.lsvp9tyne {
  d: path("M7 16.5h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_ssmh9ez {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

.qnsgwgb-f {
  d: path("M7 7.5h10");
}

</style>

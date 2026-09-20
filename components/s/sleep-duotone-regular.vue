<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d4-4pac7y"/><path class="qielwdbpe"/><path class="v105zmblb"/><path class="d63facces"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sleep-duotone-regular" /></template>
<style>
.d4-4pac7y {
  fill: currentColor;
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d63facces {
  d: path("m19 3 2 2 -2 2 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qielwdbpe {
  fill: currentColor;
  d: path("m19 3 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.v105zmblb {
  d: path("M15 3a9 9 0 1 0 0 18 7 7 0 0 1 0 -18");
}

</style>

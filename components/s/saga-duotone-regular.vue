<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dnw_0qq-m"/><path class="n1mp41bom"/><path class="gnw6lwwpf"/><path class="rcqlbvbaf"/><path class="taxmbub4q"/><path class="ltkkdtbvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:saga-duotone-regular" /></template>
<style>
.dnw_0qq-m {
  fill: currentColor;
  d: path("M3 8.25A2.25 2.25 0 0 1 5.25 6h2.5A2.25 2.25 0 0 1 10 8.25a2.25 2.25 0 0 1 -2.25 2.25h-2.5A2.25 2.25 0 0 1 3 8.25");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gnw6lwwpf {
  d: path("M3 8.25A2.25 2.25 0 0 1 5.25 6h2.5A2.25 2.25 0 0 1 10 8.25a2.25 2.25 0 0 1 -2.25 2.25h-2.5A2.25 2.25 0 0 1 3 8.25");
}

.ltkkdtbvf {
  d: path("M8.5 14.5 6 17l2.5 2.5");
}

.n1mp41bom {
  fill: currentColor;
  d: path("M14 8.25A2.25 2.25 0 0 1 16.25 6h2.5A2.25 2.25 0 0 1 21 8.25a2.25 2.25 0 0 1 -2.25 2.25h-2.5A2.25 2.25 0 0 1 14 8.25");
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

.rcqlbvbaf {
  d: path("M14 8.25A2.25 2.25 0 0 1 16.25 6h2.5A2.25 2.25 0 0 1 21 8.25a2.25 2.25 0 0 1 -2.25 2.25h-2.5A2.25 2.25 0 0 1 14 8.25");
}

.taxmbub4q {
  d: path("M6 17h12");
}

</style>

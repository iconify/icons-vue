<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppivcbbzp"/><path class="x3k3riida"/><path class="hehuylblo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rebase-outline-regular" /></template>
<style>
.hehuylblo {
  d: path("m16 5 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.x3k3riida {
  d: path("m5 14 6 -6h8");
}

</style>

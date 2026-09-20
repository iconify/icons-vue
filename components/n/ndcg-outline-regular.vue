<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="lip701r7h"/><path class="kikp0-sku"/><path class="jsj5j3bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ndcg-outline-regular" /></template>
<style>
.ffw_pwyfz {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

.jsj5j3bdw {
  d: path("M13 10.5V13");
}

.kfdmhd64i {
  d: path("m15 15 6 6");
}

.kikp0-sku {
  d: path("M10 9v4");
}

.lip701r7h {
  d: path("M7 7v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

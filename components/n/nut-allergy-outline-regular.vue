<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tbr5-0t2d"/><path class="af8xzachr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nut-allergy-outline-regular" /></template>
<style>
.af8xzachr {
  d: path("M6 19 18 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tbr5-0t2d {
  d: path("M12 3c4 3 6 7 6 11a6 6 0 0 1 -12 0c0 -4 2 -8 6 -11");
}

</style>

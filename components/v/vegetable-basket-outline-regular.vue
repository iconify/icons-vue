<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lhk-ji-wo"/><path class="z22xlf92i"/><path class="hue5ncbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vegetable-basket-outline-regular" /></template>
<style>
.hue5ncbwv {
  d: path("M7 12a5 5 0 0 1 10 0");
}

.lhk-ji-wo {
  d: path("M5 12v8h14v-8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z22xlf92i {
  d: path("M5 16h14");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tlj36_-3d"/><path class="lhk-ji-wo"/><path class="z22xlf92i"/><path class="hue5ncbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vegetable-basket-duotone-bold" /></template>
<style>
.hue5ncbwv {
  d: path("M7 12a5 5 0 0 1 10 0");
}

.lhk-ji-wo {
  d: path("M5 12v8h14v-8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tlj36_-3d {
  fill: currentColor;
  d: path("M5 12v8h14v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z22xlf92i {
  d: path("M5 16h14");
}

</style>

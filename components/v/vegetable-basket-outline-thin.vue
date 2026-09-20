<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhk-ji-wo"/><path class="z22xlf92i"/><path class="hue5ncbwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vegetable-basket-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hue5ncbwv {
  d: path("M7 12a5 5 0 0 1 10 0");
}

.lhk-ji-wo {
  d: path("M5 12v8h14v-8Z");
}

.z22xlf92i {
  d: path("M5 16h14");
}

</style>

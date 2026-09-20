<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5t072bpe"/><path class="hue5ncbwv"/><path class="tn8-gc8mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pasta-outline-thin" /></template>
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

.tn8-gc8mv {
  d: path("M10 12a2 2 0 0 1 4 0");
}

.z5t072bpe {
  d: path("M3 12h18c0 4 -4 7 -9 7s-9 -3 -9 -7");
}

</style>

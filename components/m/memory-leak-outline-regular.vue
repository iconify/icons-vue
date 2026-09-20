<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="paiz6ybie"/><path class="f99jf8yqv"/><path class="zqnyy8bad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-leak-outline-regular" /></template>
<style>
.f99jf8yqv {
  d: path("M8 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.paiz6ybie {
  d: path("M5 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.zqnyy8bad {
  d: path("M13 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>

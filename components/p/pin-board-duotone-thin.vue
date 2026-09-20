<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dejb-0bmi"/><path class="hw3hhabol"/><path class="xggn7ob2x"/><path class="gkj6vbuly"/><path class="vm6abrb1c"/><path class="fo01rcbwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pin-board-duotone-thin" /></template>
<style>
.dejb-0bmi {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fo01rcbwx {
  d: path("M14 7h5v5h-5Z");
}

.gkj6vbuly {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hw3hhabol {
  fill: currentColor;
  d: path("M6 8h5v6H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vm6abrb1c {
  d: path("M6 8h5v6H6Z");
}

.xggn7ob2x {
  fill: currentColor;
  d: path("M14 7h5v5h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

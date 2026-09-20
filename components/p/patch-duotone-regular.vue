<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j6rrwqbna"/><path class="mqv-a60sg"/><path class="k7e3clbnf"/><path class="vl61p6b9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:patch-duotone-regular" /></template>
<style>
.j6rrwqbna {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k7e3clbnf {
  d: path("M2 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.mqv-a60sg {
  fill: currentColor;
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
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

.vl61p6b9q {
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

</style>

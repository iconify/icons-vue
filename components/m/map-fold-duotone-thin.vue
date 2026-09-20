<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7d56fjnv"/><path class="vyks9vbfn"/><path class="mpjdm200q"/><path class="tkeq0bpvv"/><path class="gcnz6cc5q"/><path class="artopbq8l"/><path class="ephqv81ta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:map-fold-duotone-thin" /></template>
<style>
.artopbq8l {
  d: path("M12 7.5v9");
}

.ephqv81ta {
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
}

.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gcnz6cc5q {
  d: path("M9.5 10 12 7.5l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.tkeq0bpvv {
  d: path("M18 4v16");
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>

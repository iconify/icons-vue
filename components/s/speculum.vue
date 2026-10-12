<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ms4tis_-w"/><circle class="hrivag5vo"/><path class="iya1fi4bg"/><circle class="t64h55u3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speculum" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrivag5vo {
  cx: 15.5px;
  cy: 10.75px;
  r: 1.25px;
}

.iya1fi4bg {
  d: path("m16 12l1.75 9.25m-2-11.75l2.4-4.4");
}

.ms4tis_-w {
  d: path("M12.5 9.25L2.75 5m9.75 7.25L2.75 16.5");
}

.t64h55u3e {
  cx: 18.75px;
  cy: 4px;
  r: 1.25px;
}

</style>

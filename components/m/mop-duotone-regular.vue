<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a2c_btbtq"/><path class="kf-dg5j1v"/><path class="t9rz8abmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mop-duotone-regular" /></template>
<style>
.a2c_btbtq {
  fill: currentColor;
  d: path("M8 11c-1 4 -2 7 -2 9h12c0 -2 -1 -5 -2 -9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kf-dg5j1v {
  d: path("M12 2v9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t9rz8abmm {
  d: path("M8 11c-1 4 -2 7 -2 9h12c0 -2 -1 -5 -2 -9Z");
}

</style>

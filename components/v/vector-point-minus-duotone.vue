<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ij3-wpj1f"/><path clip-rule="evenodd" class="rd-by0huh"/><path class="v_n61vb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-point-minus-duotone" /></template>
<style>
.ij3-wpj1f {
  stroke-opacity: 0.4;
  d: path("M2 19C2 15 5 11 9 11M13 11C17 11 22 9 22 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rd-by0huh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 8H12C13.105 8 14 8.895 14 10V12C14 13.105 13.105 14 12 14H10C8.895 14 8 13.105 8 12V10C8 8.895 8.895 8 10 8H11Z");
  stroke: none;
}

.v_n61vb4y {
  d: path("M16 19H22");
}

</style>

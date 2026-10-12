<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hnxkb8bry"/><path class="jgyfg-bpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pagoda" /></template>
<style>
.hnxkb8bry {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v1.5m0 0h1q2 1 4-.25q-1 3.25-2.5 3.25v3q2.75 1 4.75-.25q-1 3.25-3 3.25h-.5v3q3.5 1 5.5-.25q-1 3.25-3 3.25H17v2H7v-2H5.75q-2 0-3-3.25q2 1.25 5.5.25v-3h-.5q-2 0-3-3.25q2 1.25 4.75.25v-3Q8 7.25 7 4q2 1.25 4 .25Z");
}

.jgyfg-bpu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

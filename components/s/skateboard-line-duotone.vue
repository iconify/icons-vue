<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xul90ei0n"/><circle class="x9u4_etvk"/><circle class="z7l_f7r4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboard-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9u4_etvk {
  cx: 7px;
  cy: 15px;
  r: 2px;
}

.xul90ei0n {
  d: path("M2 7L2.81253 8.2188C3.5544 9.3316 4.80332 10 6.14073 10H17.8593C19.1967 10 20.4456 9.33159 21.1875 8.2188L22 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z7l_f7r4c {
  cx: 17px;
  cy: 15px;
  r: 2px;
}

</style>

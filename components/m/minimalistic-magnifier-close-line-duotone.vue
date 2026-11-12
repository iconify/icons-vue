<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="r0xhknb7f"/><path class="mj_6ev9oe"/><path class="k_wd3t9ba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-close-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_wd3t9ba {
  d: path("M9.73223 9.73224L11.5 11.5M11.5 11.5L13.2678 13.2678M11.5 11.5L9.73223 13.2678M11.5 11.5L13.2678 9.73224");
}

.mj_6ev9oe {
  d: path("M20 20L22 22");
}

.r0xhknb7f {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>

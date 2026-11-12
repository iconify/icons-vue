<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="v0dnq2b7o"/><circle class="gm84d-bws"/><circle class="gradl1bjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:menu-dots-line-duotone" /></template>
<style>
.gm84d-bws {
  cx: 12px;
  cy: 12px;
  r: 2px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gradl1bjs {
  cx: 19px;
  cy: 12px;
  r: 2px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0dnq2b7o {
  cx: 5px;
  cy: 12px;
  r: 2px;
}

</style>

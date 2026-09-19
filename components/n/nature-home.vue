<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="nmntmgbnp"/><circle class="q332r2vjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nature-home" /></template>
<style>
.nmntmgbnp {
  d: path("M4.5 28.317h39z");
}

.q332r2vjg {
  cx: 24px;
  cy: 24px;
  r: 11.1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

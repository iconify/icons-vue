<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="ib21wsbmr"/><path class="be8124b7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-circle-9" /></template>
<style>
.be8124b7n {
  d: path("M19.168 30.049c.884 1.156 2.23 1.951 4.46 1.951H24a5.3 5.3 0 0 0 5.3-5.3v-5.4");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ib21wsbmr {
  cx: 24px;
  cy: 21.3px;
  r: 5.3px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

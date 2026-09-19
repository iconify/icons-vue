<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><g class="y9tr6bcfx"><circle class="zep-sybwn"/><path class="gbi5mnisa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-circle-6" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gbi5mnisa {
  d: path("M28.832 17.951c-.884-1.156-2.23-1.951-4.46-1.951H24a5.3 5.3 0 0 0-5.3 5.3v5.4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zep-sybwn {
  cx: 24px;
  cy: 26.7px;
  r: 5.3px;
}

</style>

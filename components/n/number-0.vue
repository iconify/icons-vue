<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVG0yuq5EEg" class="g-2mhzyzm"/></defs><rect class="j3s9ivbxi"/><g class="y9tr6bcfx"><use href="#SVG0yuq5EEg"/><rect class="d8cmf6beh"/><use href="#SVG0yuq5EEg"/><rect class="d8cmf6beh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:number-0" /></template>
<style>
.d8cmf6beh {
  width: 10.6px;
  height: 16px;
  x: 18.7px;
  y: 16px;
  rx: 5.3px;
  ry: 5.3px;
}

.g-2mhzyzm {
  d: path("m28.046 17.884l-8.104 12.232");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

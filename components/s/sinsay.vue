<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e3qlsnbzq"/><g class="y9tr6bcfx"><circle class="bqbko5uls"/><path class="p91u6j__w"/></g><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sinsay" /></template>
<style>
.bqbko5uls {
  cx: 32.242px;
  cy: 13.239px;
  r: 1.296px;
}

.e3qlsnbzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.804 34.005c1.062 1.381 2.393 1.896 4.245 1.896h2.563a4.32 4.32 0 0 0 4.318-4.318v-.019a4.32 4.32 0 0 0-4.318-4.318h-2.827a4.323 4.323 0 0 1-4.324-4.324a4.333 4.333 0 0 1 4.333-4.332h2.549c1.852 0 3.183.514 4.245 1.896");
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

.p91u6j__w {
  d: path("M32.242 26.241v9.816");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

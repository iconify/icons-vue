<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ucrft-blu"/><path class="kqxlr3b_s"/><path class="nbbr1f38w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ndax" /></template>
<style>
.kqxlr3b_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.976 29.997v9.488L30.583 24L13.976 8.515v9.488");
}

.nbbr1f38w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.711 34.137V43.5L39.759 24L19.711 4.5v9.363");
}

.ucrft-blu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.259 24L8.241 12.529v22.942z");
}

</style>

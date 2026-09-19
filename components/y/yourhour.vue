<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hagz1gbii"/><path class="ld2mgdm9q"/><path class="i2pculkkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yourhour" /></template>
<style>
.hagz1gbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 15.637V30.5a13 13 0 0 1-26 0v-8.363");
}

.i2pculkkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 25.855v6.5h4.645");
}

.ld2mgdm9q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 23.064a8.359 8.359 0 1 1-8.355 8.363A8.356 8.356 0 0 1 24 23.064M17.5 8.21v13.927M24 4.5v14.855M30.5 8.21v13.927");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="seslvtbbs"/><circle class="atioxb22d"/><path class="o3urp4rvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mavi" /></template>
<style>
.atioxb22d {
  cx: 36.147px;
  cy: 18.9px;
  r: 0.7px;
  fill: currentColor;
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

.o3urp4rvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.147 21.3v5.4m-9.729-2c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m0 3.3v-5.4");
}

.seslvtbbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.18 21.3l-2 5.4l-2-5.4m-17.53 2c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2v3.3m-4-5.3v5.4m4-3.4c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2v3.3");
}

</style>

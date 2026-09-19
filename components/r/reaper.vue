<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="n9qjqacjw"/><path class="wn-qe0btf"/><ellipse class="hmmbs4ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reaper" /></template>
<style>
.hmmbs4ber {
  cx: 34.221px;
  cy: 22.209px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.588px;
  ry: 4.561px;
}

.n9qjqacjw {
  cx: 13.78px;
  cy: 22.209px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.588px;
  ry: 4.561px;
}

.wn-qe0btf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.357c14.717 0 19.5-12.442 19.5-17.356s-2.77-9.358-7.136-9.358c-3.241 0-8.365 4.287-12.364 10.455c-4-6.168-9.123-10.455-12.364-10.455C7.271 10.643 4.5 15.086 4.5 20S9.284 37.357 24 37.357");
}

</style>

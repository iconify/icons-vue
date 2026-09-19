<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="b5y5-7bkj"/><path class="pt228rlnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omniclock" /></template>
<style>
.b5y5-7bkj {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M25.5 24a1.5 1.5 0 1 1-1.5-1.5a1.5 1.5 0 0 1 1.5 1.5Z");
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

.pt228rlnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.4 23.476l12.58-3.98m-27.304 17.82L22.9 25.01");
}

</style>

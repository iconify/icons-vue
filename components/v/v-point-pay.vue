<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a1yy6hbvi"/><path class="dpt7s486k"/><circle class="upxwd5bwx"/><path class="ao73bib1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:v-point-pay" /></template>
<style>
.a1yy6hbvi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.299 41H8c-2.216 0-4-1.784-4-4V8c0-2.216 1.784-4 4-4h29c2.216 0 4 1.784 4 4v23.26");
}

.ao73bib1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.35 41v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H34.35");
}

.dpt7s486k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4 22.5L22.5 41L41 22.5M5.169 5.169L22.5 22.5L39.831 5.169");
}

.upxwd5bwx {
  cx: 37px;
  cy: 37px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

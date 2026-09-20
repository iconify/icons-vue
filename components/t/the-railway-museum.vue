<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ya90am3mm"/><circle class="t8uqyobui"/><circle class="k3f1y1rbn"/><path class="okvvshb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-railway-museum" /></template>
<style>
.k3f1y1rbn {
  cx: 38.625px;
  cy: 24px;
  r: 4.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.okvvshb1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.812 24h29.25");
}

.t8uqyobui {
  cx: 24px;
  cy: 24px;
  r: 4.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ya90am3mm {
  cx: 9.375px;
  cy: 24px;
  r: 4.875px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

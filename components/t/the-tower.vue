<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d3kl-6b7u"/><path class="p5cnj3bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-tower" /></template>
<style>
.d3kl-6b7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.25 6.247h-20.5L3.5 24l10.25 17.754h20.5L44.5 24z");
}

.p5cnj3bhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.75 15.773h-9.5L14.5 24l4.75 8.227h9.5L33.5 24z");
}

</style>

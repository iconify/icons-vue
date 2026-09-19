<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty-rod3bw"/><path class="diwxr46pu"/><path class="qsmnwdbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reroll" /></template>
<style>
.diwxr46pu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.25 13.72l-5.22 19.47l19.46-5.22z");
}

.qsmnwdbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.49 27.97l2.05-17.51l-16.29 3.26zM21.25 13.72L5.5 19.04l10.53 14.15zm-5.22 19.47l12.93 9.31l-18.5-4.96zm19.46-5.22L28.96 42.5L42.5 28.96zM19.04 5.5l2.21 8.22m.47 14.36V20.8h2.44a2.45 2.45 0 1 1 0 4.89h-2.44m2.44 0l2.42 2.42");
}

.ty-rod3bw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.04 5.5l18.5 4.96l4.96 18.5L28.96 42.5l-18.5-4.96l-4.96-18.5z");
}

</style>

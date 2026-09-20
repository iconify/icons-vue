<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ht-k_vgcf"/><rect transform="rotate(23.198 35.707 24)" class="t3ily9b8a"/><path class="dotjtgggk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wide-walls" /></template>
<style>
.dotjtgggk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.133 11.797za4.23 4.23 0 0 0-5.552 2.221l-6.066 14.154a1.643 1.643 0 0 1-2.962.122l-1.222-2.31a6.76 6.76 0 0 1 .056-6.426l.788-1.426l-.003-.001c.599-.84.902-1.905.743-3.047a4.24 4.24 0 0 0-3.71-3.604A4.23 4.23 0 0 0 4.5 15.683c0 .396.058.777.16 1.14l-.002.004l.007.017q.156.54.44 1.01l6.324 14.535a6.08 6.08 0 0 0 5.355 3.652l.05.002q.555.075 1.101.04l.056.002v-.004a5.65 5.65 0 0 0 4.797-3.41l6.566-15.321a4.23 4.23 0 0 0-2.221-5.553");
}

.ht-k_vgcf {
  cx: 32.143px;
  cy: 32.316px;
  r: 4.229px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t3ily9b8a {
  width: 8.457px;
  height: 26.552px;
  x: 31.478px;
  y: 10.724px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.229px;
  ry: 4.229px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="pas2o9p9o"/><rect class="in2p2izxd"/><path class="ov-b5kbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-swords-of-ditto" /></template>
<style>
.in2p2izxd {
  width: 12.836px;
  height: 4.127px;
  x: 17.582px;
  y: 14.97px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.452px;
  ry: 1.452px;
}

.ov-b5kbgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 36.089V19.097M21.936 7.542v7.428m4.939 4.127l1.024 20.621L24 44.5l-3.899-4.782l1.024-20.621m4.939-11.555v7.428");
}

.pas2o9p9o {
  width: 6.717px;
  height: 4.042px;
  x: 20.826px;
  y: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.829px;
  ry: 0.829px;
}

</style>

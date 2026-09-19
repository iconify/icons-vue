<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dfiah1vrd"/><path class="xit0mgb8p"/><path class="mw0v4ob5v"/><path class="o04ae2qis"/><path class="wora-yq9m"/><path class="cf8phl9jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wgu" /></template>
<style>
.cf8phl9jp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.002a1.568 1.568 0 0 0-3.137 0v6.244");
}

.dfiah1vrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.603 21.255a2.27 2.27 0 1 0 2.27 2.27");
}

.mw0v4ob5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.397 21.255a2.27 2.27 0 1 0 2.27 2.27");
}

.o04ae2qis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.136 27.247a5.658 5.658 0 1 0 7.125-8.602s5.48-3.802 9.239-7.328c-2.307-1.395-9.25-.317-12.451 1.07c0 0-2.625-1.396-7.05-1.396s-7.048 1.396-7.048 1.396C13.75 11 6.807 9.922 4.5 11.317c3.758 3.526 9.239 7.328 9.239 7.328a5.658 5.658 0 1 0 7.125 8.602");
}

.wora-yq9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.002v10.554c0 .48-.591.71-.915.354l-3.349-3.675");
}

.xit0mgb8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.161 17.626a9.9 9.9 0 0 1 1.701 5.569c0 5.5-4.46 9.96-9.96 9.96a10 10 0 0 1-2.057-.213l.03-.027L24 37.334l-4.874-4.42l.03.028q-.999.21-2.058.212c-5.5 0-9.96-4.459-9.96-9.96c0-2.062.627-3.979 1.701-5.568");
}

</style>

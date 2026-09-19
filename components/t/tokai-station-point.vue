<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="leyjyl0yh"/><circle class="k48vvuogk"/><path class="s8wj4t3zk"/><path class="pty1_5o6t"/><path class="y2emzu5hg"/><circle class="d0knxkblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tokai-station-point" /></template>
<style>
.d0knxkblz {
  cx: 19.081px;
  cy: 27.775px;
  r: 0.75px;
  fill: currentColor;
}

.k48vvuogk {
  cx: 36.179px;
  cy: 24px;
  r: 6.821px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.leyjyl0yh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.84 27.159v-6.317h1.917c1.085 0 1.963.95 1.963 2.121s-.878 2.122-1.963 2.122H34.84");
}

.pty1_5o6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.427 27.498c.287.347.647.476 1.147.476h.693c.645 0 1.167-.485 1.167-1.085s-.522-1.085-1.167-1.085h-.764c-.646 0-1.169-.486-1.169-1.085s.524-1.086 1.171-1.086h.69c.5 0 .86.13 1.146.476m2.118.093v3.228c0 .3.262.543.585.543h.175m-1.374-2.875h1.227m4.128 1.791c0 .599-.52 1.085-1.161 1.085h-.408c-.425 0-.769-.322-.769-.72s.344-.718.77-.718h1.57");
}

.s8wj4t3zk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.563 30.82H5v-8.859l8.282-4.782l8.282 4.782zm-4.906-11.691h14.748M13.282 17.18H36.18M21.563 28.872h9.842m-9.842 1.949H36.18M30.09 17.18v1.948m-2.437 0V17.18m-7.307 0v1.95m-2.436 0v-1.95m7.307 0v1.95m-2.436 0v-1.95m7.796 11.692v1.949m-2.436 0v-1.95m-2.435 0v1.95m-2.436 0v-1.95");
}

.y2emzu5hg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.152 25.382c.282-.262.48-.285 1.024-.285c.617 0 1.023.252 1.023.933v1.943");
}

</style>

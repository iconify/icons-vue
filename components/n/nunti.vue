<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9k0evbcj"/><path class="mvrx74b1u"/><ellipse class="g0rc-7z-p"/><path class="pjul67b0n"/><path class="omlrtdbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nunti" /></template>
<style>
.g0rc-7z-p {
  cx: 24px;
  cy: 31.627px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.646px;
  ry: 5.379px;
}

.mvrx74b1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.451s-1.329 1.123 17.052 12.364L43.5 26.17s-.098-2.701-.52-6.3s-9.976-9.395-12.932-11.332S26.126 6.961 24 6.961");
}

.omlrtdbqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.7 14.339a3.227 3.227 0 0 1 4.664.055m-7.01 17.259a8.68 8.68 0 0 0 9.292 0");
}

.pjul67b0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.904 23.834v4.36m14.192-4.36v4.36M21.7 14.339c.09-.074-.033-7.368-.033-7.368m4.697 7.423c.091-.074-.031-7.423-.031-7.423M21.7 14.339s1.18.592-17.2 11.832m21.864-11.777S25.12 14.93 43.5 26.17");
}

.w9k0evbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.868 26.587a14.873 14.873 0 0 1-29.738-.093M24 15.451s1.329 1.123-17.052 12.364L4.5 26.17s.098-2.701.52-6.3s9.976-9.395 12.933-11.332S21.873 6.961 24 6.961");
}

</style>

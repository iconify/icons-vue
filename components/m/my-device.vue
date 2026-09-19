<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(90 24 24)" class="kqc501bgm"/><path class="p459mp70l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-device" /></template>
<style>
.kqc501bgm {
  width: 39px;
  height: 25px;
  x: 4.5px;
  y: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.p459mp70l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.596 21.568a6.5 6.5 0 1 0-9.192 0M17.5 29.472h13m-13 7h13");
}

</style>

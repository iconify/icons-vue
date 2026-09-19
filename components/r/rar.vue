<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ycnsr2bgk"/><path class="bdykbub8l"/><rect class="xz63ew-ch"/><path class="cr0oj8bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rar" /></template>
<style>
.bdykbub8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 29.83H7.5a2 2 0 0 0-2 2v7.67a2 2 0 0 0 2 2H18m12 0h10.5a2 2 0 0 0 2-2v-7.67a2 2 0 0 0-2-2H30m-20.63-14v-7m0 18.67v-7m0 18.67v-7");
}

.cr0oj8bcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30 15.33a6 6 0 1 0-12 0m0 .89h12v3.88H18z");
}

.xz63ew-ch {
  width: 12px;
  height: 39px;
  x: 18px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

.ycnsr2bgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 6.5H7.5a2 2 0 0 0-2 2v7.67a2 2 0 0 0 2 2H18m12 0h10.5a2 2 0 0 0 2-2V8.5a2 2 0 0 0-2-2H30M18 18.17H7.5a2 2 0 0 0-2 2v7.66a2 2 0 0 0 2 2H18m12 0h10.5a2 2 0 0 0 2-2v-7.66a2 2 0 0 0-2-2H30");
}

</style>

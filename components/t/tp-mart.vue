<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c_438gb6y"/><path class="bd3kk6bbo"/><path class="v1hm6nxew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tp-mart" /></template>
<style>
.bd3kk6bbo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.857 36.04v-1.463a1.153 1.153 0 1 0 0-2.306v-1.465a1.153 1.153 0 1 0 0-2.306v-1.462a1.153 1.153 0 1 0 0-2.308v-1.462a1.153 1.153 0 1 0 0-2.306v-1.465a1.153 1.153 0 1 0 0-2.306V15.73a1.153 1.153 0 1 0 0-2.308V11.96c.638 0 1.155-.517 1.154-1.154h1.447a1.155 1.155 0 0 0 2.308 0h1.447a1.155 1.155 0 0 0 2.309 0h1.447a1.155 1.155 0 0 0 2.308 0h1.447a1.155 1.155 0 0 0 2.308 0h1.447a1.153 1.153 0 1 0 2.306 0h1.449a1.153 1.153 0 1 0 2.306 0h1.45c0 .637.516 1.153 1.153 1.153v1.463a1.155 1.155 0 0 0 0 2.308v1.462a1.153 1.153 0 1 0 0 2.306v1.464a1.153 1.153 0 1 0 0 2.307v1.462a1.155 1.155 0 0 0 0 2.308V28.5a1.153 1.153 0 1 0 0 2.306v1.464a1.153 1.153 0 1 0 0 2.306v1.463c-.637 0-1.154.517-1.154 1.154h-1.45a1.153 1.153 0 1 0-2.305 0h-1.45a1.153 1.153 0 1 0-2.305 0h-1.447a1.155 1.155 0 0 0-2.309 0h-1.446a1.155 1.155 0 0 0-2.309 0h-1.447a1.155 1.155 0 0 0-2.308 0h-1.447a1.155 1.155 0 0 0-2.308 0h-1.447c0-.637-.517-1.153-1.154-1.153");
}

.c_438gb6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.857 41.23H41.18V10.805h-4.038V6.77H6.82v30.423h4.037z");
}

.v1hm6nxew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.035 15.103a7.02 7.02 0 0 1-14.039 0");
}

</style>

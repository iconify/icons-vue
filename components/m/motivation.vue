<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="x76jkybwm"/><path class="tqqkht_xz"/><path class="lpzjz3bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:motivation" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lpzjz3bkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.017 22.039c0 3.79-.724 5.554-2.297 6.22");
}

.tqqkht_xz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.578 22.039c0 3.79-.724 5.554-2.298 6.22m-4.263-6.22c0-1.27-1.028-2.298-2.297-2.298s-2.298.812-2.298 2.081s1.029 1.99 2.298 1.99c1.153 0 2.237.873 1.979 1.71");
}

.x76jkybwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.578 22.039c0-1.27-1.029-2.298-2.298-2.298s-2.297.812-2.297 2.081s1.028 1.99 2.297 1.99c1.153 0 2.237.873 1.98 1.71");
}

</style>

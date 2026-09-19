<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x8hogibeh"/><rect class="xbqoyrbch"/><path class="ae_tuwb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mynumber-card-check-app" /></template>
<style>
.ae_tuwb6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21 23.5h16V32H21zm-6.25.375c-.831 0-1.5.669-1.5 1.5v1c0 1.387.676 1.297.676 2.684c-2.325 0-2.307 1.45-2.307 2.566h6.762c0-1.071-.083-2.566-2.307-2.566c0-1.298.676-1.204.676-2.684v-1c0-.831-.67-1.5-1.5-1.5z");
}

.x8hogibeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 13.5c0-2.216 1.784-4 4-4m0 29c-2.216 0-4-1.784-4-4m39 0c0 2.216-1.784 4-4 4m0-29c2.216 0 4 1.784 4 4");
}

.xbqoyrbch {
  width: 30px;
  height: 20px;
  x: 9px;
  y: 14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

</style>

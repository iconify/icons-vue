<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7wsgtbyd"/><path class="f_ui-xbcy"/><path class="xtk8scbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metrobank-online" /></template>
<style>
.f_ui-xbcy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.308 17.417L22.285 5.97c.95-.68 2.48-.68 3.43 0l15.977 11.447c.95.681.95 1.777 0 2.458L25.715 31.322c-.95.681-2.48.681-3.43 0L6.308 19.875c-.95-.68-.95-1.777 0-2.458M5.6 18.646h36.8");
}

.n7wsgtbyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 22.905L25.97 34.753c-1.05.606-2.998.596-3.99 0L5.5 22.907V42.54h37z");
}

.xtk8scbrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.74V5.54l-9.312 13.106zl9.311-13.094L24 5.54");
}

</style>

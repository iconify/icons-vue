<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yg8e8-b1d"/><circle class="wmpzgibar"/><path class="qy7t02uii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mini" /></template>
<style>
.qy7t02uii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 19.672H32.209m9.423 2.868h-8.468m5.609 2.859h-5.599m2.731 2.868h-3.664");
}

.wmpzgibar {
  cx: 24px;
  cy: 24px;
  r: 9.28px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yg8e8-b1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.753 21.823v4.354m-6.32-.005v-4.349l2.177 4.354l2.177-4.347v4.347m3.927 0v-4.354l2.884 4.354v-4.354m1.966 0v4.354M3.5 19.672h12.291M6.368 22.54h8.467m-5.607 2.859h5.598m-2.731 2.868h3.664");
}

</style>

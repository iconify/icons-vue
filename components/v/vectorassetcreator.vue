<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x2hxv4buc"/><circle class="serkfacbc"/><circle class="vv-dkjbxy"/><path class="r89j-i99e"/><path class="vlkulbcwx"/><path class="r-ojezxov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vectorassetcreator" /></template>
<style>
.r-ojezxov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.269 34.148h1.5v-1.5m-.046-3.578q-.053-.75-.166-1.489");
}

.r89j-i99e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.751 33.87l32.531-7.791M7.775 34.148h1.5");
}

.serkfacbc {
  cx: 5.775px;
  cy: 34.148px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vlkulbcwx {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 2.909 2.909;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.184 34.148h27.631");
}

.vv-dkjbxy {
  cx: 42.225px;
  cy: 25.614px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x2hxv4buc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.538 23.739a18.5 18.5 0 0 0-2.264-4.184l2.59-2.551a3.022 3.022 0 0 0-4.282-4.266l-.002.002l-2.55 2.6a18.41 18.41 0 0 0-21.515 0l-2.57-2.57a3.17 3.17 0 0 0-2.171-.916a2.98 2.98 0 0 0-2.122.876a3.02 3.02 0 0 0 0 4.264l2.599 2.55a18.5 18.5 0 0 0-3.476 10.807v1.797m13.63-5.613a2.92 2.92 0 1 1-2.921-2.92a2.92 2.92 0 0 1 2.92 2.92m10.547 2.02a2.92 2.92 0 1 1 4.904-1.171");
}

</style>

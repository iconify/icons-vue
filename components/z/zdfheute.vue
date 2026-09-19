<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wfo1ezq4r"/><path class="wxaxtxbpm"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zdfheute" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wfo1ezq4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.067 26.616v3.3a2 2 0 0 0 4 0v-3.3m0 3.3v2m-17.524-8v8m.001-3.3a2 2 0 0 1 4 0v3.3m-3.997-16.05h4l-4 5.3h4m6.46 9.75a1.94 1.94 0 0 1-1.7 1a2.006 2.006 0 0 1-2-2v-1.3a2 2 0 0 1 4 0v.7h-4m14.31-4.4v6a.945.945 0 0 0 1 1h.3m-2.301-5.3h2.1m-11.41-8.75a2 2 0 0 0-4 0v1.3a2 2 0 0 0 4 0m0 2v-8m3.862 8v-6.6a1.367 1.367 0 0 1 1.4-1.4a1.56 1.56 0 0 1 1.4.6m-3.9 2.1h2.8m12.289 15.05a1.94 1.94 0 0 1-1.7 1a2.006 2.006 0 0 1-2-2v-1.3a2 2 0 1 1 4 0v.7h-4");
}

.wxaxtxbpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M9.544 34.834h4");
}

</style>

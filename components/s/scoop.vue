<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grbit1bbl"/><path class="ppepjvb7w"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scoop" /></template>
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

.grbit1bbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.064 21.952a8.936 8.936 0 0 1 17.872 0m0 6.398a8.936 8.936 0 1 1-17.872 0");
}

.ppepjvb7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 4.75;
  d: path("M15.064 28.35v-6.4m17.872.002v6.397m-21.358-9.306h3.701m-3.701 6.144h3.289m-3.289 6.145h3.701M32.72 19.043h3.702m-3.339 6.144h3.339m-3.702 6.145h3.702M20.207 13.634l-2.92-2.92m10.483 2.954l2.95-2.949m-9.727 11.379h6.064m-6.064 6.179h6.064");
}

</style>

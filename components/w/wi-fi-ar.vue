<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qi2l_1nto"/><path class="qo_-0itvt"/><circle class="u4drktb-u"/><path class="xuu2h3jhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wi-fi-ar" /></template>
<style>
.qi2l_1nto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.531 5.5c7.322.642 12.874 6.892 12.66 14.253S27.072 33.03 19.726 33.244C12.379 33.458 6.14 27.896 5.5 20.56m0-2.423c.587-6.72 5.905-12.049 12.613-12.637");
}

.qo_-0itvt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.411 18.743a6.944 6.944 0 0 1 6.307-6.319");
}

.u4drktb-u {
  cx: 19.322px;
  cy: 19.349px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xuu2h3jhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.148 29.163L42.5 42.5");
}

</style>

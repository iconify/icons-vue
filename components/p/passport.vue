<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="o4rai1ufi"/><path class="o2elzjj2p"/><path class="t-__tvi-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:passport" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.o2elzjj2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.061 9.914h12v12h-12zm22.891.088h-6.976v12.193h12.017v-7.474");
}

.o4rai1ufi {
  cx: 31.868px;
  cy: 31.956px;
  r: 5.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t-__tvi-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.952 10.002c.49.054.982.108 1.602.42c.62.313 1.37.884 1.94 1.468s.962 1.177 1.182 1.651s.269.827.317 1.18M15.048 38.086h6.976V25.893H10.007v7.474m5.041 4.719c-.49-.053-.981-.107-1.602-.42c-.62-.312-1.37-.884-1.94-1.467s-.962-1.178-1.182-1.651s-.269-.827-.317-1.18");
}

</style>

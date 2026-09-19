<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb8-9xb7t"/><path class="hrr_xrbpp"/><path class="v7iq98vcq"/><circle class="p-rtlcbbp"/><path class="kodpx-dju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pear-launcher-pro" /></template>
<style>
.cb8-9xb7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.147 13.579c.766 0 3.016.325 4.962 2.105c1.748 1.597 2.357 3.595 2.559 5.022a5 5 0 0 0 1.514 2.94c.79.75 1.678 1.801 2.382 3.212c1.09 2.183 1.348 3.07 1.215 5.217c-.067 1.067-.63 4.718-3.713 7.761c-3.58 3.532-7.999 3.664-8.919 3.664s-5.34-.132-8.918-3.664c-3.084-3.043-3.647-6.694-3.713-7.761c-.133-2.146.124-3.034 1.214-5.217a11.5 11.5 0 0 1 2.382-3.212a5 5 0 0 0 1.515-2.94c.202-1.427.81-3.425 2.558-5.022c1.947-1.78 4.196-2.106 4.962-2.106Z");
}

.hrr_xrbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.017 14.968c.13-2.377.468-5.604-1.857-8.901c1.683 2.828 3.245 2.863 4.39 2.898");
}

.kodpx-dju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.308 13.811l5.193-5.193m-.121 3.32l-1.6-1.599");
}

.p-rtlcbbp {
  cx: 11.224px;
  cy: 15.895px;
  r: 2.948px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v7iq98vcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.488 4.557c2.347-.411 3.575 1.51 7.236 2.03c-.955 1.736-3.592 5.136-6.975 5.171S28.498 9.78 28.48 8.149s2.013-3.242 4.008-3.592");
}

</style>

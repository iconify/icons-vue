<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="u61j93bnk"/><path class="yzrcswbqc"/><path class="nhp0f4bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tesla-one" /></template>
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

.nhp0f4bfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.272 13.861L24 17.146l3.728-3.285");
}

.u61j93bnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.531 14.485A42.9 42.9 0 0 1 24 10.951a42.9 42.9 0 0 1 16.469 3.534");
}

.yzrcswbqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.58 18.2a9 9 0 0 1-2.468-1.586c3.564-2.05 10.16-2.753 10.16-2.753L24 41.194l3.728-27.333s6.597.703 10.16 2.753A9 9 0 0 1 35.42 18.2");
}

</style>

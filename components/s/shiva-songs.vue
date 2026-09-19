<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="owl2j47-t"/><circle class="k6whz4dvb"/><path class="hy1u3pb7q"/><path class="alm5-ubzj"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shiva-songs" /></template>
<style>
.alm5-ubzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.392 27.058a2 2 0 0 1 2 2v1.3a2 2 0 1 1-4 0v-1.3a2 2 0 0 1 2-2m-11.398 5.299a2 2 0 0 1-2-2v-1.3a2 2 0 1 1 4 0v1.3a2 2 0 0 1-2 2m-8.84-.876c.491.639 1.106.877 1.962.877H13.3a1.996 1.996 0 0 0 1.996-1.996v-.009a1.996 1.996 0 0 0-1.996-1.996h-1.306a2 2 0 0 1-1.998-1.997h0c0-1.106.896-2.002 2.002-2.002h1.178c.856 0 1.471.237 1.962.876m19.466 6.701c.366.307.76.447 1.645.447h.449c.73 0 1.322-.593 1.322-1.325h0c0-.732-.592-1.325-1.322-1.325h-.897c-.73 0-1.322-.593-1.322-1.325h0c0-.732.591-1.325 1.322-1.325h.448c.886 0 1.28.14 1.645.447m-11.199 4.828v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3");
}

.hy1u3pb7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.654 15.643v5.3m-12.644-.876c.49.639 1.105.877 1.96.877h1.185a1.996 1.996 0 0 0 1.996-1.996v-.009a1.996 1.996 0 0 0-1.996-1.996H13.85a2 2 0 0 1-1.998-1.997h0c0-1.106.896-2.002 2.002-2.002h1.178c.856 0 1.471.237 1.962.876m19.166 5.123a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2m-.001 3.3v-5.3m-3.767 11.415v6a2 2 0 0 1-3.414 1.414");
}

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

.k6whz4dvb {
  cx: 24.654px;
  cy: 13.193px;
  r: 0.75px;
  fill: currentColor;
}

.owl2j47-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.509 15.643l-2 5.3l-2-5.3m-7.708-2.7v8m0-3.3a2 2 0 1 1 4 0v3.3");
}

</style>

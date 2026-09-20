<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2mczh0kh"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:slickdeals" /></template>
<style>
.j2mczh0kh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 33.184c.548 1.258 1.476 1.727 2.909 1.727h1.983c1.845 0 3.724-1.764 4.198-3.94c.473-2.175-.64-3.939-2.486-3.939h-2.19c-1.846 0-2.958-1.763-2.485-3.939c.473-2.175 2.352-3.939 4.198-3.939h1.983c1.433 0 2.36.47 2.909 1.727m-7.65 15.993l4.282-19.696m14.108 18.049L37.5 11.126m-3.079 14.16c.724-3.327-1.07-6.025-4.009-6.025c-2.937 0-5.906 2.698-6.63 6.025l-.85 3.917c-.724 3.327 1.07 6.024 4.009 6.024s5.905-2.697 6.629-6.024");
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

</style>

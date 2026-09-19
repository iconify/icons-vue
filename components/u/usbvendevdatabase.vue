<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxeddob4x"/><path class="nltyrdb-k"/><path class="eerscfb9s"/><path class="f_3dgj_tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:usbvendevdatabase" /></template>
<style>
.eerscfb9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.7 14.2l8.4-2.1a3.68 3.68 0 0 1 3 .5l7.6 7.1c.9 1.4 1.8 2.7-.4 5.7l-9.9 5.7");
}

.f_3dgj_tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.1 14.5l4.8-1.5l3.5 2.5l.1 2.9l-2.6 1.6m2.5-4.6l-4.7 2.4m2.5 2.9l-10.5 4.4l-4 1.9M5.6 22.3l7.9 11.3m13.6-6.2c1.7 1.7.4 4.4-1.2 5.8m-7.3-16.1c-.5-.8-1.1-1.5-1.9-1.5");
}

.nltyrdb-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.9 31.8a2.22 2.22 0 0 0 2.5 1.3l4.1-2c2-2.1 1.4-3.8.9-5.5l-9.6-11.4l-4.5 1.2c-1.8.8-2 1.3-1.7 2.5");
}

.zxeddob4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.6 17.1L6 20.3l8.4 12.1l12.7-5.1Zm-4.2 15.3l-1.6 3.5l12.6-4.7l1.8-3.9M6 20.3l-1.5 3.8l8.3 11.8");
}

</style>

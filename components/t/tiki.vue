<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hi28t0c_c"/><circle class="lind4nnjg"/><path class="uth63gb2r"/><circle class="gx81kxt_w"/><path class="v38mo3b4b"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tiki" /></template>
<style>
.gx81kxt_w {
  cx: 35.831px;
  cy: 16.659px;
  r: 3.669px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hi28t0c_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 23.585h7.737M12.368 35.01V23.585m8.358 11.421V23.59M35.83 35.006V23.59m-10.619 0v11.416m6.135 0l-4.694-5.708l4.694-5.669m-4.7 5.669h-1.435");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.lind4nnjg {
  cx: 20.726px;
  cy: 16.659px;
  r: 3.669px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uth63gb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.696 16.66a1.97 1.97 0 0 1-3.94 0z");
}

.v38mo3b4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.8 16.66a1.97 1.97 0 0 1-3.94 0z");
}

</style>

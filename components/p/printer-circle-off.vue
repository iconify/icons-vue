<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r1uw6x1jt"/><path class="c3t1z7f-g"/><path class="iumjt1xah"/><path clip-rule="evenodd" class="z8g30dfux"/><path class="jbieuxnxx"/><path class="yypq_mbev"/><path class="z70afl_me"/><path clip-rule="evenodd" class="ksag4bb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:printer-circle-off" /></template>
<style>
.c3t1z7f-g {
  fill: currentColor;
  d: path("M9 6v4a1 1 0 0 1-2 0V6c0-1.068.776-2 1.833-2h8.334C18.224 4 19 4.932 19 6v4a1 1 0 1 1-2 0V6z");
}

.ft5dv1b6b {
  fill: none;
}

.iumjt1xah {
  fill: currentColor;
  d: path("M7 9h12a3 3 0 0 1 3 3v5a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3");
}

.jbieuxnxx {
  fill: currentColor;
  d: path("M9 19.8V15a1 1 0 1 0-2 0v4.8c0 1.154.727 2.2 1.833 2.2h8.334C18.273 22 19 20.954 19 19.8V15a1 1 0 1 0-2 0v4.8a.7.7 0 0 1-.029.2H9.029A.7.7 0 0 1 9 19.8");
}

.ksag4bb-q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.r1uw6x1jt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8 10V6c0-.552.373-1 .833-1h8.334c.46 0 .833.448.833 1v4");
}

.yypq_mbev {
  fill: currentColor;
  d: path("M10 19a.5.5 0 0 1 0-1h6a.5.5 0 0 1 0 1zm0-2a.5.5 0 0 1 0-1h6a.5.5 0 0 1 0 1z");
}

.z70afl_me {
  fill: currentColor;
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.z8g30dfux {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8 15v4.8c0 .663.373 1.2.833 1.2h8.334c.46 0 .833-.537.833-1.2V15");
}

</style>
